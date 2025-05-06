# Portable LIDAR 3D Data Collection System for VR Environment Building  
*A project by Abdullah Abadi (Buffalo State University, Computer Information Systems)*  

---

## 📌 Overview  
This repository documents the development of a portable LIDAR system for capturing 3D spatial data to build computational virtual reality (VR) environments. Field tests were conducted at Buffalo State University’s **Technology Building** and **Science and Mathematics Complex (SAMC)**.  

**Key Features:**  
✔️ Portable LIDAR system integration (hardware/software)  
✔️ Field data collection and processing pipeline  
✔️ 3D modeling in ArcGIS Pro and point cloud visualization  

---

## 📂 Repository Structure  
Portable-LIDAR-VR-Mapping/
├── data/ # Raw & processed point clouds (.las, .ply)
├── docs/ # Project paper, poster, and presentations
├── hardware/ # Component specs and assembly guide
└── README.md # You are here!


---

## 🔧 System Components  
- **LIDAR Scan Head**: Leishen C16 Series (Shanghai, China)  
- **GPS Unit**: For geospatial accuracy  
- **Laptop**: Runs data acquisition software  
- **Portable Power Supply**: Field operation support  

*(See [hardware/components_list.md](hardware/components_list.md) for details.)*  

---

## 📊 Methodology  
1. **Data Acquisition**  
   - Scanned the Technology Building using systematic LIDAR passes.  
   - Captured RGB images for texture mapping.  

2. **Data Processing**  
   - Filtered noise and aligned point clouds using **Upper Computer** platform.  
   - Classified structures in **ArcGIS Pro**.  

3. **3D Visualization**  
   - Generated measurable VR-ready models from point clouds.  

---

📝 Key Findings
✅ Captured partial 3D structures of the Technology Building.
⚠️ Limitations: Incomplete coverage due to system constraints.
🔧 Future Work: Optimize scanning strategy for full-building reconstruction.

(See docs/LIDAR_presentation.pdf for detailed results.)

📚 References
Jensen, J. R. (2003). Remote Sensing of the Environment.

Leishen C16 Manual (https://www.monualsite.com/manual/20809171/Leishen-Intelligent-System-C16-Series.html)

Video Tutorial (https://www.youtube.com/watch?v=HEOoEc363As)

🙏 Acknowledgements
Funded by Buffalo State University’s Office of Undergraduate Research and NSF SUW I.SAMP Grant.
Special thanks to:

Dr. Tao Tang (Mentor)

Dr. Sanbani Banerjee (Grant support)

Mr. Jonathan Rosten & Dr. James Mayrose (Engineering Technology Dept.)



