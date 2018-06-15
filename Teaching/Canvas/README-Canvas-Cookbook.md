# Canvas Cookbook

## Content From GitHub

**On GitHub:**

1. Create repository for content for Canvas.
2. Enable GH Pages.
3. `README.md` for info on the repositiory.
4. `index.md` for the Canvas pages.
5. Create an `_config.yml` with the contents:

   ``` yaml
   remote_theme: douglasurner/canvas
   ```   

**In Canvas:**

1. Create the item in Canvas.
2. Paste this HTML in:

   ```HTML
   <p>
     <iframe src=""
       width="100%" height="666px">
     </iframe>
   </p>
   ```
   The `src` of the iframe is the URL on GH Pages site of the page that you want displayed in the iframe.
