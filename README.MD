================================

SVG Animation Creator – Advanced

================================

Overview:
-----------
SVG Animation Creator is a web‐based tool designed to convert animated GIFs or 
sequences of images (e.g., PNGs) into fully animated, scalable SVG files. It has 
been optimized for NFT artists and creators who need to mint fully on‑chain 
digital artworks with the smallest file sizes possible – every byte counts!

Key Features:
---------------
•   **Input Flexibility:**  
    - Upload a single animated GIF (which is parsed into individual frames)  
    - Batch upload image sequences (PNG, etc.) with customizable frame durations

•   **Advanced Frame Control:**  
    - Set the total animation duration and adjust the duration of each frame  
    - Automatically calculate frame timings for smooth, discrete animations

•   **Optimized SVG Output:**  
    - Generates responsive animated SVG files (scalable across mobile, desktop, 
      and various browsers)  
    - Utilizes sprite sheet techniques to minimize file size  
    - Offers advanced SVG optimization (removes unnecessary whitespace and metadata)  
    - Provides real-time file size estimation

•   **Compression & Download Options:**  
    - Set the number of colors used during compression (default value of 256 for 
      optimal file size reduction)  
    - Download the generated SVG file directly  
    - Copy the SVG code or a Data URI for fully on‑chain integration

•   **User-Friendly Interface:**  
    - Reset functionality to quickly revert to default settings  
    - Status messages for real-time feedback during file processing and SVG generation

Technical Details:
--------------------
•   **Core Technologies:**  
    - HTML5, CSS3, and modern JavaScript (ES6+ features, template literals, etc.)  
    - Runs in modern browsers and is designed for integration within environments 
      like Wix and other embeddable platforms.

•   **Libraries Used:**  
    - **omggif:** For decoding animated GIF frames  
    - **pako:** For data compression (deflate/inflate functionality)  
    - **UPNG.js:** For PNG encoding and color quantization for the sprite sheet

•   **Build & Compatibility:**  
    - The code is written with advanced optimizations for maximum byte efficiency 
      (critical for fully on‑chain NFTs)
    - Uses ES6 template literals and modern syntax; if using VS Code or another 
      IDE, ensure your JavaScript target is set to ES6 or later to avoid false 
      warnings.
    - Includes a “@ts-nocheck” pragma to disable TypeScript checking if needed.

Usage Instructions:
---------------------
1. **Configure Animation Settings:**
   - Set the number of frames, total animation duration, and select the scaling 
     mode (pixelated for pixel art or smooth for general images).
   - Adjust the compression level (default 256) to balance image quality and file size.
   - Optionally enable advanced SVG optimization for extra byte savings.

2. **Upload Frames:**
   - Use “Upload Animated GIF” for a single GIF file or “Batch Upload Images” for 
     multiple images. The tool will automatically process and display each frame 
     for further editing.
   - Adjust individual frame durations if needed.

3. **Generate & Optimize SVG:**
   - Click the “Generate SVG” button to create an animated SVG using a sprite sheet 
     approach.
   - Use the “Optimize/Compress SVG” button to apply further optimizations.
   - Preview the animation in the built‑in preview panel.

4. **Export Options:**
   - Copy the generated SVG code to your clipboard.
   - Download the SVG file directly.
   - Copy a Data URI of the SVG for fully on‑chain integration in NFT contracts.

5. **Reset Function:**
   - Click “Reset Form” to revert all settings to default and clear the current 
     frames list.

Installation & Deployment:
-----------------------------
•   Simply upload the HTML file (with the associated minified library scripts for 
    omggif, pako, and UPNG.js) into your web project.
•   The tool is designed to be embedded (for example, on a Wix site) or hosted on 
    your own domain.
•   Ensure the JavaScript target/environment supports ES6+ syntax (or disable the 
    type-checker using the “@ts-nocheck” directive).

Contributing:
--------------
•   Contributions and feedback are welcome – feel free to suggest improvements or 
    bug fixes via GitHub issues or pull requests.
•   Maintain consistency with the current code style and include clear commit 
    messages that reference the changes made.

License:
---------
Distributed under an MIT-style license. See the LICENSE file for details.

Contact:
---------
For any questions or feedback, please contact the developer ([@jams2blues](https://github.com/jams2blues)).

=====================================================================
