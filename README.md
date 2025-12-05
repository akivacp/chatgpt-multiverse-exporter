# ChatGPT Multiverse Exporter (v8.3)

**A userscript to capture and export ChatGPT conversation data as JSON files.**

The **ChatGPT Multiverse Exporter** allows you to capture and export the entire conversation data from ChatGPT, including **all branches**, even if the content was regenerated. It provides an easy-to-use, draggable interface for exporting the data as a **JSON file**, which can be visualized with the **ChatGPT JSON Tree Viewer** or stored for later use.

## Features

- **Draggable Badge and Export Button**:  
  Move the **badge** and **export button** anywhere on the screen. Both UI elements are linked, so they always stay together and within the viewport.
  
- **Captures All Conversation Branches**:  
  The tool captures **all branches of the conversation**, including **regenerated messages**. Even if a message or section is re-generated, the exporter will record the full chat history.

- **Export Conversations as JSON**:  
  You can easily export your entire conversation, including regenerated messages, as a downloadable **JSON** file. This file is compatible with the **ChatGPT JSON Tree Viewer** for further visualization.

- **Persistent UI**:  
  The badge and button are always visible, even if you scroll or resize the window. They remain **fixed** in place and can be repositioned as needed.

- **Conversation ID Tracking**:  
  Automatically associates the captured data with the conversation’s **ID** to ensure each export is unique to the session.

- **Local Storage for UI Position**:  
  The positions of the draggable badge and button are stored in **local storage**, so they persist even across page reloads.

- **No External Data Transmission**:  
  The tool is entirely **client-side**, which means no data is uploaded or sent to any external server. The data remains in the browser until you choose to export it.

## Privacy Considerations

- **All data processing is local**: The script only processes conversation data within your browser, and the data never leaves your computer unless you manually export it.
- **You control your data**: You are in full control of when and how your data is captured and exported. No third-party access to your conversations.
- **No external servers involved**: The exporter does not send any data to external servers, ensuring complete privacy and security.

## Installation

To use this exporter, you need a browser extension like **[Tampermonkey](https://www.tampermonkey.net/)** or **[Violentmonkey](https://violentmonkey.github.io/)** to run the script.

### Steps:
1. Install **Tampermonkey** (or **Violentmonkey**) on your browser.
2. Download and add the script from **[GreasyFork](https://greasyfork.org/en/scripts/456055-chatgpt-exporter)**.
3. After installation, go to any **ChatGPT conversation page** (e.g., `chat.openai.com` or `chatgpt.com`).
4. Use the **"Export Multiverse"** button to capture and export your conversation as a **JSON** file.

## Usage

1. **Loading Conversations**:  
   Visit any ChatGPT conversation page to load the chat.
   
2. **Exporting JSON**:  
   Click the **"Export Multiverse"** button to download the conversation as a **JSON file**. The file will contain all branches of the conversation, including regenerated parts.

3. **Draggable UI**:  
   Move the **badge** and **export button** to any position on the screen. They are linked and will move together to keep the UI accessible at all times.

4. **Refreshing the Snapshot**:  
   Click the **badge** to refresh the conversation data snapshot.

## Demo

To see the exporter in action, install the script using **Tampermonkey** or **Violentmonkey**, visit a **ChatGPT conversation**, and start using the tool.

## Exporting JSON Files

To use this viewer, you'll need to export your ChatGPT conversations as JSON files. One tool I recommend for this is the [ChatGPT Multiverse Exporter](https://github.com/akivacp/chatgpt-multiverse-exporter), which is available on GitHub.

This exporter tool captures **all conversation branches**, including regenerated parts, and exports them as JSON files that can be used with the **ChatGPT JSON Tree Viewer**.

- [ChatGPT Multiverse Exporter on GitHub](https://github.com/akivacp/chatgpt-multiverse-exporter)

While this tool is recommended for compatibility, you can also use any tool that generates a valid JSON file.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! If you have ideas for new features, improvements, or bug fixes, feel free to fork the repository and submit a pull request.  

### How to Contribute:
1. Fork this repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to your branch (`git push origin feature/your-feature`).
5. Create a pull request with a description of your changes.

## Acknowledgements

- **[ChatGPT JSON Tree Viewer](https://github.com/akivacp/chatgpt-json-tree-viewer)**: This exporter is compatible with the **ChatGPT JSON Tree Viewer** for visualizing exported conversation data.

---

### Need Help?

If you run into issues or have any questions, feel free to open an issue on the GitHub repository, and I'll do my best to assist you.

