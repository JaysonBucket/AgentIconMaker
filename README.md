# Microsoft 365 Icon Creator (Teams Apps & Copilot Agents)

This is part of a broader set of Copilot agent and learning materials. Check out my projects site to get an overview:
https://www.jaysons.dev

## Summary
A guided Microsoft 365 icon creation agent that helps generate compliant icons for both Microsoft Teams apps and Copilot agents, supporting motif, background, color, and style customization (with Fluent UI defaults) and producing 192×192 color icons and 32×32 outline icons in a structured step-by-step workflow.

<img width="444" height="377" alt="image" src="https://github.com/user-attachments/assets/a3b8eb52-f5a9-4bb6-b96a-67654e7b0b4e" />


---

## 🚀 Overview

This agent provides a guided design workflow to create Microsoft 365–compliant icons that can be used as:

- Copilot Agent avatars (Agent Builder)
- Microsoft Teams app icons
- Messaging extension icons
- App Bar / Favorites icons

Users are guided through motif, background, color, and style choices and can optionally upload a reference image to influence the design.

---

## ✨ Features

- Guided intake workflow (Motif, Background, Style, Tone)
- Fluent UI–compatible default color presets
- Optional reference image upload
- Sequential asset generation
- Microsoft Teams–compliant output
- Copilot Agent–ready avatar support

Generates:

| Asset | Size | Use Case |
|-------|------|----------|
| Color Icon | 192×192 PNG | Copilot Agent Avatar / Teams Store |
| Outline Icon | 32×32 PNG | Teams App Bar / Messaging Extension |

---

## 🧭 How It Works

1. The agent asks for:
   - Motif (e.g. shield, chat bubble, abstract symbol)
   - Background type (solid, gradient, transparent)
   - Style (minimal, academic, modern)
   - Tone (friendly, neutral, authoritative)

2. The agent generates:
   - Asset A (192×192 Color Icon)

3. After approval:
   - Asset B (32×32 Outline Icon)

---

## 🧰 Usage

Add the provided Agent Instruction to your Copilot Agent and use one of the included Starter Prompts such as:
Create a Microsoft 365 icon for a Copilot agent (also suitable for Teams). Motif: [[MOTIF]]. Background: [[BACKGROUND]]. Style: [[STYLE]]. Tone: [[TONE]]. Please suggest Fluent UI color defaults and generate Asset A.

---

## 📦 Output

The agent produces:

- A square 192×192 PNG Color Icon  
- A 32×32 PNG Outline Icon (white + transparency)

Both assets can be used across Microsoft 365 surfaces depending on context.

---

## 🛡️ Compliance Notes

- No rounded corners are applied
- Icons are generated square
- Outline icons contain only:
  - White (#FFFFFF)
  - Transparency
- Enterprise-safe design language only

---

## 🤝 Contributing

Contributions, ideas, and improvements are welcome!  
Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.


