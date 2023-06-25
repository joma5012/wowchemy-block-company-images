# Wowchemy Company Images Block

## Add the Block to your Site

1. Install the block by referencing it in your `config/_defaults/config.yaml`:
   ```yaml
   module:
     imports:
       # Your block's GitHub URL (replace <USERNAME> and <COLLECTION-NAME> with your GitHub username and block collection name)
       - path: github.com/<USERNAME>/wowchemy-block-company-images
   ```
1. Create an instance of your block in `home/`, for example let's create `home/my-block.md`:
   ```markdown
   ---
   # Replace <USERNAME> and <BLOCK-NAME> with your GitHub username and block name, respectively.
   widget: 'github.joma5012.wowchemy-block-company-images'

   # This file represents a page section.
   headless: true

   # Order that this section appears on the page.
   weight: 1

   title: Hello
   ---

   Welcome to my new block!
   ```

