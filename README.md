# AutoMass for Unity
Automatically calculate the mass of GameObjects in Unity based on volume and density.

---

## 📦 Features
- Right-click any GameObject in the hierarchy to quickly **add an AutoMass component**.
- Supports **density presets** (Stone, Wood, Gold, etc.) or **custom densities**.
- Adjustable **voxel size** for volume precision.
- Customizable **density presets** via the Settings window.
- Adds an **"Apply AutoMass"** button to Rigidbody inspectors that aggregates child masses automatically.

---

## 🧩 How It Works

1. **Right-click** a GameObject in the **Hierarchy**  
   → Select `Add AutoMass`

   <img src="Documentation/ObjectMenu.png" alt="AutoMass Overview" style="width: 400px;"/>

2. The `AutoMass` component will appear on the selected GameObject.
   
   <img src="Documentation/Component.png" alt="AutoMass Overview" style="width: 400px;"/>
   
   Choose a **preset material** or enter a **custom density** (kg/m³).

   <img src="Documentation/Component2.png" alt="AutoMass Overview" style="width: 400px;"/>

3. Open **AutoMass Settings** to modify presets or voxel resolution.

   <img src="Documentation/Settings.png" alt="AutoMass Overview" style="width: 400px;"/>

4. On any GameObject with a `Rigidbody`, click **"Apply AutoMass"** at the bottom of the Rigidbody inspector.  
   → The mass of all child AutoMass components will be summed and applied.

   <img src="Documentation/Rigidbody.png" alt="AutoMass Overview" style="width: 400px;"/>

---

## 📌 Notes
- Volume is estimated using voxelization of the object's mesh.
- Make sure your MeshRenderer or SkinnedMeshRenderer is present for accurate results.
- Best suited for static or semi-static objects with defined geometry.

---

## 🛠 Installation
1. Import the `.unitypackage` into your project.
2. You’re ready to go! Right-click an object in the Hierarchy to begin.

---

## 🧪 Compatibility
- Unity 2020.3 and above
- Works in both URP and HDRP
- No third-party dependencies

---

## 📮 Support
For questions, feature requests, or bug reports:  
📧 your@email.com  
🐛 GitHub Issues: [link if available]

---

