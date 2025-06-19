# Welcome to the CUBEAI Documentation

CUBEAI is a next-generation medical AI platform designed to empower radiologists with intuitive, real-time tools for segmentation model creation, annotation, and deployment — all without requiring AI expertise.

---

## 🚀 What is CUBEAI?

CUBEAI enables radiologists to independently develop and refine segmentation models using clinical data. The system seamlessly integrates with PACS servers, foundational models, and a self-configuring training engine to streamline every stage of the AI pipeline.

### 🌐 Key Features

- **End-to-End Automation**: From PACS data fetching to model deployment, all steps are automated.
- **Interactive Annotation Tools**: Powered by foundational models like SAM, Vista3D, and nnInteractive.
- **Self-Configuring Training**: Based on nnU-Net architecture and enhanced with MONAI Label, tailored for clinical use.
- **Model Bank**: Store and access trained models for assisted segmentation tasks.
- **Web-Based Interface**: Full workflow from your browser with no coding required.

---

## 📚 Documentation Structure

Use the sidebar to explore:

- 📖 [Overview](overview.md): Get the big picture of the platform and its capabilities.
- 💻 [Frontend](frontend.md): Learn about workflow creation, PACS integration, and the UI.
- 📂 [Data Management](data.md): Explore how workflows, metadata, and labels are stored.
- 🧠 [Backend](backend.md): See how model training, scheduling, and deployment are automated.
- 🧬 [Foundation Models](foundation-models.md): Dive into the integration of SAM, Vista3D, and nnInteractive.
- 🛠️ [Self-Configuring Models](self-configuring.md): Learn how training adapts to new datasets.
- 📦 [Deployment](deployment.md): Understand how trained models are made available for inference.

---

## 👩‍⚕️ For Radiologists

- No prior AI experience required.
- Use point-click tools for annotation.
- Review, train, and deploy with minimal effort.

## 👨‍💻 For Developers

- Backend powered by MONAI and nnU-Net.
- PostgreSQL for metadata storage.
- Easily extendable architecture for new tasks and modalities.

---

## 🧪 Example Result

> On the LITS dataset, a model trained via CUBEAI achieved a **Dice score of 0.84** using just prompt-based annotations from SAM.

---

## 📫 Feedback & Contributions

Have suggestions or want to contribute?  
Feel free to open issues or pull requests on [GitHub](https://github.com/AhmedXAlDeeb/CUBEAI.github.i)
