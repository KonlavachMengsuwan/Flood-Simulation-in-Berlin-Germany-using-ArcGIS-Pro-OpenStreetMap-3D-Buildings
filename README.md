# 🌊 Flood Simulation in Berlin, Germany using ArcGIS Pro + OpenStreetMap 3D Buildings
![2](https://github.com/user-attachments/assets/0138ff1c-b3ca-4502-ab63-831545a0e8d6)

This repository shows how to create a basic flood simulation in **Berlin, Germany** using ArcGIS Pro's **Rainfall Simulation** tool, with **OpenStreetMap 3D Buildings & Trees** as visualization.

## 🚀 Quick Steps

### 1️⃣ Set Up the Scene

1. **Create a New Project**
   - Open ArcGIS Pro → `New Project` → choose **Local Scene**.

2. **Add 3D Buildings**
   - Open the `Catalog` pane.
   - Go to `Living Atlas` → search **"OpenStreetMap 3D"**.
   - Select **OpenStreetMap 3D Buildings & Trees** → click **Add and Open**.

3. **Set Basemap**
   - Go to `Map` → `Basemap` → select **Imagery**.

4. **Style 3D Buildings**
   - In `Contents` pane → right-click **OpenStreetMap 3D Buildings** → `Symbology`.
   - Set:
     - **Primary symbology:** `Unique Values`
     - **Field 1:** `building`

5. **Navigate to Berlin**
   - Use search bar or zoom manually to **Berlin City Center**.

6. **Zoom to Your Area of Interest**
   - Focus on a specific district or neighborhood.

---

### 2️⃣ Run Rainfall Simulation

7. **Open Rainfall Simulation**
   - Go to `Analysis` → `Simulation` → `Rainfall`.

8. **Set Simulation Parameters**
   - Choose **area from camera view** → `Create Simulation in Area`.
   - Set:
     - **Duration:** `00:10:00` (10 minutes)
     - **Rainfall/hr:** `200 mm`
     - **Evaporation/hr:** `0 mm`

9. **Run Simulation**
   - Click **Run** to simulate flood over Berlin city with 3D buildings.

✅ Done! You will see water accumulation displayed on the 3D cityscape.

---

## 🎨 Example Result

Here’s an example flood simulation map in Berlin:
![4](https://github.com/user-attachments/assets/e65fa459-d3e5-4362-8aec-b0af2413f8e0)
![3](https://github.com/user-attachments/assets/dad396df-6303-4780-b103-c3bee8e19939)
![1](https://github.com/user-attachments/assets/f67d2416-25d5-4629-a98c-e304a88510dd)

---

## 💡 Future Improvements

To make the simulation more realistic:

- ✅ Import a **high-resolution DEM** for elevation surface
- ✅ Incorporate drainage network and infrastructure data
- ✅ Adjust rainfall/evaporation parameters for different scenarios
- ✅ Export flood extent for GIS analysis

---


---

## 🤝 License

Feel free to use, share, or modify this guide!

---


