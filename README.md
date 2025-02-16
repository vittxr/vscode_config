# Summary

VS Code now supports extension and settings isolation through [profiles](https://code.visualstudio.com/docs/editor/profiles). In this repository, I've included some of the profiles I use.

# How to import it 

1. in vscode, press `ctrl + shift + p`
2. select the option `> Preferences: Open Profiles (UI)`
3. right click in the sidebar and click in `Import Profile` option.

![image](https://github.com/user-attachments/assets/91fb0415-37d6-4d03-af4b-78ef1c0e3726)


# Profiles setup

#### Python profiles (fastapi, python, flask, etc)

For Python, you need to have `mypy` installed in your virtual environment (venv). In the IDE, make sure you're using the Python interpreter from the virtual environment by selecting it in the bottom right corner of VS Code.

![image](https://github.com/user-attachments/assets/60efaddc-f60f-4f2a-887e-accdaf67fbc4)

# Settings.json

I have have a custom style customization for my vscode, so each profile contains the data of [settings.json](). You may need to install some vscode UI extensions, so check the `settings.json` of your vscode using

![image](https://github.com/user-attachments/assets/4e38e957-aae7-4b5f-86df-fc12fd836778)

The highlighted values are extensions that need to be installed (or it may be invalid, an outdated config value)
