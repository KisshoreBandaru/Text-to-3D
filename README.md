# 3D Model Generation from Text using Shap-E (OpenAI)

This project shows how we can use AI to generate 3D models just by giving text prompts like:

> “a christmas tree”, “a dragon”, “iphone”, etc.

We used **OpenAI’s Shap-E model** and ran it on **Google Colab** using GPU.

--- * * *---

## Goal

To demonstrate how a machine learning model (Shap-E) can turn **text** into a **3D asset**. This is useful for game developers, AR/VR creators, or designers.

---* * *---

##Why Shap-E?

We chose Shap-E because:

- It’s built by OpenAI (reliable and official)
- It can turn **text → 3D model**
- It works on Google Colab (no need for personal GPU)
- Compared to other models like DreamFusion or Zero123, it’s lightweight and easier to run

--- * * *---

## How It Works (Step-by-Step)

### 1.Setup

We cloned the repo:
```bash
git clone https://github.com/openai/shap-e.git
pip install -e shap-e
