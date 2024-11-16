# V6 Engine CAD Modelling and Process Development

## **Overview**
This project focuses on the **CAD modelling, process selection, and manufacturing analysis** of a **V6 Engine assembly**, incorporating over **25 parts** and **5 major subassemblies**. The aim is to develop virtual product designs, optimize the manufacturing process, and evaluate 3D printing file formats for production.

---

## **Objectives**
1. **CAD Modelling**:
   - Develop 3D models for various components of the V6 engine, including crankshafts, pistons, connecting rods, and more.
   - Use advanced SolidWorks features for detailed designs.
2. **Process Selection**:
   - Evaluate manufacturing processes for critical components like the connecting rod.
   - Compare **forging**, **machining**, and **casting** processes for high production efficiency.
3. **3D Printing Format Analysis**:
   - Analyze file formats (STL, IGES, STEP) for their compatibility with 3D printing and manufacturing.

---

## **Features and Components**

### **1. Engine Crankshaft**
- **Design Features**:
  - Utilized **move/copy**, **chamfer**, and **fillet** tools for designing complex features.
  - Rotated camshaft pairs by ±120° for symmetry.
- ![Crankshaft 3D Model](HossainA007/V6-Engine-CAD-MODELLING/pics/1.png)

---

### **2. Piston V6 Assembly**
- **Design Details**:
  - Includes components like the cylinder head and nuts, assembled using **hole wizard**, **extrude**, and **chamfer** tools.
- ![Piston Assembly](path/to/piston.png)

---

### **3. Connecting Rod**
- **Process Selection**:
  - Preferred **forging** due to its strength, material efficiency, and ability to withstand high inertial forces.
  - Comparison of **sand casting**, **permanent mold casting**, and **die casting** for batch sizes of 10,000+.
- **Operation Sequence**:
  - Milling, drilling, chamfering, and oil hole machining were optimized for cost-effectiveness.
- ![Connecting Rod](path/to/connecting_rod.png)

---

### **4. Full Engine Housing**
- **Assembly Features**:
  - **Concentric**, **coincident**, and **width selection** mates for accurate part alignment.
- ![Engine Housing](path/to/engine_housing.png)

---

## **Process Selection**
1. **Forging for Connecting Rods**:
   - **Primary Process**:
     - High fatigue strength and reduced machining make forging the best choice.
   - **Alternative Processes**:
     - Sand casting for intricate designs, though less efficient for large production batches.
2. **Machining Processes**:
   - Sequence includes engraving, milling, drilling, and laser cutting for precision manufacturing.

---

## **3D Printing File Formats**
1. **STL Format**:
   - Widely used for 3D printing.
   - Lacks support for color and texture data.
2. **IGES Format**:
   - Retains curvature details but prone to data loss in complex models.
3. **STEP Format**:
   - Supports colors, tolerance, and material properties, making it ideal for data-rich applications.

---

## **Images**
1. **Crankshaft Design**  
   ![Crankshaft Design](path/to/crankshaft.png)
2. **Piston Assembly**  
   ![Piston Assembly](path/to/piston.png)
3. **Engine Housing**  
   ![Engine Housing](path/to/engine_housing.png)
4. **Connecting Rod**  
   ![Connecting Rod](path/to/connecting_rod.png)

---

## **How to Use**
1. **CAD Modelling**:
   - Open provided CAD files in SolidWorks or any compatible CAD software.
   - Modify or analyze components as needed.
2. **3D Printing**:
   - Use STL files for 3D printing with software like Ultimaker Cura.
   - Analyze IGES and STEP formats for additional design details.
3. **Process Analysis**:
   - Follow the provided manufacturing processes for production planning.

---

## **Acknowledgments**
This project was supervised by **Professor Sylvie Castagne** and **Bey Vrancken** as part of the Virtual Product Development course at **KU Leuven**.

---
