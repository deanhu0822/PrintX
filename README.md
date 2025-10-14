
## Text-to-CAD

### Overview  
This converts natural language into dimensionally accurate CAD models, enabling rapid prototyping for engineers, designers, and makers.

---


### Features  
- 🧠 **LLM-powered prompt interpretation**  
- 📐 **Accurate CAD model generation**  
- 🖼️ **Interactive 3D visualization** with PyVista in Streamlit  
- ⚡ **One-click STL export** for rapid fabrication workflows  

---

### How It Works  
1. Enter a design prompt in natural language  
2. The system generates a CAD script and converts it into an STL  
3. Visualize the output in-browser with full 3D interaction  
4. Download and fabricate directly  

---

### Technologies Used  
- [Streamlit](https://streamlit.io/) – Frontend interface  
- [PyVista](https://docs.pyvista.org/) – 3D rendering engine  
- [OpenAI API](https://openai.com/) – Language model backend  
- [Trimesh](https://trimsh.org/) – STL file handling  

---

### Getting Started  

```bash
git clone https://github.com/yourusername/PrintX.git
cd PrintX
python3 -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
streamlit run PrintX.py
```

🔑 **Note**: You must set your OpenAI API key in the script.

---

### Contributions 
We're open to collaboration! Feel free to fork the repo, suggest features, or raise issues.

