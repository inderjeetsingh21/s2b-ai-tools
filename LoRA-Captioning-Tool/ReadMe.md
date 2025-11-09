# 🎨 LoRA Caption Tool

**AI-Powered Multi-Image Captioning for Training Datasets**

A production-ready, client-side web application for creating and managing structured captions for LoRA (Low-Rank Adaptation) training datasets. No server required - runs entirely in your browser!

---

## ✨ Features

### 🤖 AI-Powered Captioning

- **Multiple AI Providers**: OpenRouter, OpenAI, n8n workflows
- **Custom Models**: Use any vision model from OpenRouter
- **Structured Output**: 8-field format (Subject, Appearance, Clothing, Pose, Setting, Lighting, Art Style, Notable Details)
- **Caption Styles**: Natural language, Danbooru tags, or hybrid

### 📁 Dataset Management

- **Import Existing Datasets**: Load images with their .txt caption files
- **Batch Processing**: Caption multiple images at once
- **Mass Editing**: Find & replace, prefix/suffix, bulk operations
- **Smart Matching**: Automatically pairs images with caption files

### 💾 Export Options (No Windows Security Warnings!)

- **Save to Folder**: Direct file system write (Chrome/Edge 86+) - **RECOMMENDED**
- **Individual Downloads**: Each image + .txt file separately
- **ZIP Export**: Traditional archive download (may trigger warnings)

### 🎨 Advanced Customization
- **Editable Prompts**: Full control over AI instructions
- **Trigger Words**: Auto-prepend custom tokens
- **Prefix/Suffix**: Add quality tags to all captions
- **Re-Caption Mode**: Replace existing captions with new AI-generated ones

---

### Usage

1. **Open the Tool**: Simply open `lora-caption-tool-production.html` in your browser
2. **Configure API**: Select provider and enter your API key
3. **Upload Images**: Drag & drop or click to upload
4. **Caption**: Click "Caption All Images" or caption individually
5. **Export**: Use "Save to Folder" for zero security warnings

---

## 📖 Usage Guide

### Creating New Captions

```
1. Select AI Provider (OpenRouter recommended)
2. Enter API Key
3. Choose Caption Style (Natural/Tags/Hybrid)
4. Optional: Set trigger word and prefix
5. Upload images
6. Click "✨ Caption All Images"
7. Edit captions as needed
8. Export to folder or download
```

### Importing Existing Datasets

```
1. Click "📁 Import Existing Dataset"
2. Use Ctrl+A to select all files in your folder
3. Images and .txt files are automatically matched
4. Edit captions using Find & Replace or manual editing
5. Export updated dataset
```

### Mass Editing Operations

- **Apply Prefix to All**: Add quality tags like "masterpiece, best quality"
- **Find & Replace**: Update terminology across all captions
- **Re-Caption All**: Replace all captions with fresh AI generations

---

## 🔒 Privacy & Security

- ✅ **100% Client-Side**: Runs entirely in your browser
- ✅ **No Data Storage**: Nothing stored on servers
- ✅ **No Tracking**: Zero analytics or telemetry
- ✅ **API Keys**: Never saved, only in browser memory
- ✅ **Your Images**: Stay on your device
- ⚠️ **Third-Party APIs**: Data sent to chosen AI provider only

---

## 🛠️ Technical Details

### Supported Models (OpenRouter)
- Gemini 2.0 Flash (Fast & affordable)
- GPT-4o (Balanced performance)
- Claude 3.5 Sonnet (Most detailed)
- Llama 3.2 Vision (Open source)
- Qwen 2 VL 72B (Cost-effective)
- Custom models (Any OpenRouter vision model)

### File Formats
- **Input**: JPG, PNG, WEBP, GIF, BMP
- **Captions**: Plain text (.txt files)
- **Export**: ZIP, individual files, or direct folder save

---

## 📝 Caption Structure

All captions follow this structured format:

```
Subject: [main subject description]
Appearance: [physical features, colors, characteristics]
Clothing: [all clothing items and accessories]
Pose: [body position and gesture]
Setting: [background and environment]
Lighting: [lighting conditions and mood]
Art Style: [artistic style, medium, quality]
Notable Details: [other important elements]
```

