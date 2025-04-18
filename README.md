# MoleScope AR 🔬  
**3D & AR Molecule Viewer for Web & Mobile**

MoleScope lets users upload `.mol` or `.pdb` molecule files and view them in interactive 3D or AR mode. The app uses Hugging Face and OpenAI APIs to generate intelligent molecule summaries — ideal for scientists, educators, or curious minds.

---

## 🚀 Features  
- 📁 Upload `.mol` and `.pdb` files  
- 🧬 Visualize molecules in 3D  
- 📱 AR mode on mobile using WebXR  
- 🤖 AI-powered summaries via Hugging Face and OpenAI  
- 🔄 Load predefined files using query params (e.g., `?compound=Caffeine`)

---

## 🌐 Live Demo  
[https://molescope.efraprojects.com](https://molescope.efraprojects.com)

---

## ⚙️ Tech Stack  
- React + Vite  
- Three.js + A-Frame (WebXR)  
- Hugging Face Inference API  
- OpenAI GPT-4 API  
- HTML5 + CSS

---

## 📂 Project Structure
```
/src  
  /components  
    MoleculeViewer.js — 3D/AR molecule renderer  
  /services  
    moleculeParser.js — File parser for .mol and .pdb  
/public  
  /sample-molecules — Sample files (Caffeine, Imatinib, etc.)
```

---

## 🔐 Environment Variables  
Before running, create a `.env` file in the root directory with:

```env
REACT_APP_HF_API_KEY=your_huggingface_api_key  
REACT_APP_OPENAI_API_KEY=your_openai_api_key
```

These keys are required for generating molecular summaries.

---

## 🛠️ Setup Instructions  
```bash
npm install  
npm run dev
```

To build for production:  
```bash
npm run build
```

---

## 🧠 Credits  
- Three.js + A-Frame for immersive molecule rendering  
- Hugging Face + OpenAI for NLP-based molecule summarization

---
