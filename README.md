# 🦕 AR Encyclopedia: Dinosaurs Edition

**AR Encyclopedia** is an educational Augmented Reality app developed with Unity and Vuforia. This edition focuses on bringing prehistoric creatures to life through image targets. Users can scan printed images of dinosaurs like the **Spinosaurus**, **Tyrannosaurus Rex (T-Rex)**, and **Triceratops** to view detailed 3D models and learn fascinating facts in AR.

---

## 🧠 What You Can Do

- 📱 Scan real images of dinosaurs using your mobile device.
- 🦖 View lifelike 3D models of Spinosaurus, T-Rex, and Triceratops.
- 🎓 Learn educational facts and features about each dinosaur.
- 🔊 Hear information via audio narration (optional).
- 📚 Great for kids, students, and dinosaur lovers.

---

## 🧩 Image Targets Used

| Dinosaur     | Description | Image Target |
|--------------|-------------|--------------|
| **Spinosaurus** | The largest known carnivorous dinosaur with a sail-like spine. | `spinosaurus.jpg` |
| **Tyrannosaurus Rex (T-Rex)** | The king of the dinosaurs, known for its powerful jaws. | `trex.jpg` |
| **Triceratops** | A herbivorous dinosaur with three horns and a large frill. | `triceratops.jpg` |

> Make sure to print the image targets or display them on another screen for scanning.

---

## 🛠 Built With

- **Unity** (Recommended: 2020.3 LTS or newer)
- **Vuforia Engine** (Version: 11.3.4+)
- **3D Models**: Dinosaur models in FBX/GLTF format
- **Android/iOS Build Support**

---

## 🔧 How to Use

1. **Download & Install the App** (or build it yourself from Unity).
2. **Print or display the image targets** for:
   - Spinosaurus
   - T-Rex
   - Triceratops
3. Open the app and point your camera at the image.
4. Watch the corresponding dinosaur appear in AR and read/listen to facts.

---

## 🏗️ How to Set Up the Project (Dev Instructions)

1. Open the project in Unity.
2. Import **Vuforia Engine** using the `.unitypackage` from [Vuforia Developer Portal](https://developer.vuforia.com/).
3. Enable Vuforia in `Project Settings > Player > XR Settings`.
4. Add an **AR Camera** and **Image Targets** from `GameObject > Vuforia Engine`.
5. Get a free **Vuforia license key** and paste it in `AR Camera > Vuforia Configuration`.
6. Create a target database on Vuforia's portal and upload your image targets (e.g., `spinosaurus.jpg`).
7. Download the database and import it into Unity.
8. Add your 3D dinosaur models as children of each Image Target.
9. Customize text, UI, and optionally audio narrations.
10. Build for Android or iOS.

---

## 📸 Preview

*(Insert screenshots or screen recordings showing each dinosaur in AR here)*

---

## 🗣️ Fun Facts (Displayed In-App)

- **Spinosaurus**: Lived about 100 million years ago and could possibly swim.
- **T-Rex**: Had the strongest bite force of any land animal.
- **Triceratops**: Used its horns for defense and possibly mating displays.

## 🙌 Credits

- Unity and Vuforia
- 3D models from Sketchfab and free asset libraries
- Background research from natural history museums and verified sources

---

## 🔮 Future Plans

- Add more dinosaurs and prehistoric creatures
- Include multilingual audio narration
- Add animations and interactivity (e.g., roaring, walking)
