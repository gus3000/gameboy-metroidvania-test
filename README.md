# Setup Github actions

- setup exports "Windows", "Linux" and "Web" in godot editor
- copy godot.ci.yml from here : https://github.com/gus3000/gameboy-metroidvania-test/blob/main/.github/workflows/godot-ci.yml and put it in your project, in `.github/workflows/`. You should adapt the following constants at the top of the file : `GODOT_VERSION`, `EXPORT_NAME` and `PROJECT_PATH` (the directory containing the `project.godot` file). 
- enable Github Pages in github project and configure it the following way :

## How do I enable and configure Github Pages ?
1. Go to your project on github.com
2. Create if needed the `gh-pages` branch :
    1. click on `main` above the file list, you should see a menu pop with the message "Find or create a branch"
    2. type `gh-pages`
    3. click on "Create branch `gh-pages` from `main`"
3. Go to your github project settings
4. In the left menu go to "Pages". You should now be at url like `https://github.com/MY_USERNAME/MY_PROJECT/settings/pages`.
5. Enable Github Pages
6. Set the source to "Github Actions" (or branch ??? TODO)
7. In Settings > Actions > General, in the category "Workflow permissions" give read and write permissions and save

Now every time 
