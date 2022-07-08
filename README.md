## Preview
![image](https://user-images.githubusercontent.com/42176949/177915130-483de33a-f4f9-4488-ac73-1c7a1aaf6b1e.png)

### Theme
Theme used: `Just Black`
https://marketplace.visualstudio.com/items?itemName=nur.just-black

### Usage
1. install extension `Custom CSS and JS Loader`
  https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css
  
2. Add to settings.json:
  `"vscode_custom_css.imports": [""]`
  
  VERY IMPORTANT: Items in `vscode_custom_css.imports` must be URLs. Plain file paths are NOT URLs.
  - Windows File URL Example: `file:///C:/Users/MyUserName/Documents/custom.css`
    - The C:/ part is REQUIRED.
  - MacOS and Linux File URL Example: `file:///Users/MyUserName/Documents/custom.css`
3. Activate command "Reload Custom CSS and JS".
4. Restart.
