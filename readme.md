### Ultra Lightweight Human Detection

<img width="1536" height="1024" alt="BCO a1e4964a-56a6-4730-91d7-9a888ff3b049" src="https://github.com/user-attachments/assets/2ac72043-3586-4ab4-b00b-493dd79cd8d0" />

### 🚀 What This Project Is  
A streamlined deep learning solution for **human detection** that prioritizes **speed, efficiency, and deployability**. Unlike heavyweight object detection frameworks, this project focuses on **ultra-compact models** that run seamlessly on constrained hardware while delivering reliable results.

---

## ✨ Key Features
- **Compact Models**: From *Ront* (0.13M params) to *Large* (30M params).  
- **Lightning-Fast Inference**: As low as **0.24 ms** on Core i9 CPUs.  
- **Flexible Input Formats**: RGB, YUV422, luminance-only, ternarized, binarized.  
- **Embedded Ready**: Supports ONNX, TFLite, and ESP‑DL (ESP32‑S3).  
- **Refined Dataset**: Built on MS‑COCO, enhanced for meaningful detection beyond benchmarks.  

---

## 🖼️ Detection Samples

**INPUT**  
<img width="64" height="64" src="https://github.com/user-attachments/assets/7b21a5fe-95eb-4eae-9a4f-13e46bda4477" />

**OUTPUT**  
<img width="640" height="427" src="https://github.com/user-attachments/assets/e7d8b915-a9ea-47fc-a07d-9d3a34f8ab66" />

---

**INPUT**  
<img width="64" height="64" src="https://github.com/user-attachments/assets/0699a92e-4ee9-4c23-b8b5-73711f9b97c1" />

**OUTPUT**  
<img width="480" height="360" src="https://github.com/user-attachments/assets/86ffb871-8841-47dc-90ad-84a05adb51a4" />

---

**INPUT**  
<img width="64" height="64" src="https://github.com/user-attachments/assets/c05a7b29-c227-4fc7-a194-27a04ae7b796" />

**OUTPUT**  
<img width="480" height="360" src="https://github.com/user-attachments/assets/cc2ab57e-ab0c-4105-85cd-726da92a2044" />

---

**INPUT**  
<img width="64" height="64" src="https://github.com/user-attachments/assets/63a7e85e-0f7e-4d58-a271-0b51d0c6d88a" />

**OUTPUT**  
<img width="480" height="360" src="https://github.com/user-attachments/assets/9c8ce9f6-b449-4984-bb45-c209d459211e" />

---

## 📊 Model Variants

| Variant | Params | Latency (Core i9) | File Size |
|--------|--------|-------------------|-----------|
| R (Ront) | 0.13M | 0.24 ms | 863 KB |
| Y (Yocto) | 0.29M | 0.28 ms | 1.2 MB |
| Z (Zepto) | 0.51M | 0.32 ms | 2.1 MB |
| A (Atto) | 0.78M | 0.37 ms | 3.2 MB |
| F (Femto) | 1.12M | 0.44 ms | 4.5 MB |
| P (Pico) | 1.52M | 0.50 ms | 6.1 MB |
| N (Nano) | 1.98M | 0.60 ms | 8.0 MB |
| T (Tiny) | 2.49M | 0.70 ms | 10 MB |
| S (Small) | 3.07M | 0.81 ms | 12.3 MB |
| L (Large) | 30.92M | 7.16 ms | 123.7 MB |

---

## ⚙️ Deployment Targets
- **ONNX** → Desktop/server inference.  
- **ESP‑DL INT8** → Quantized models for ESP32 hardware.  
- **TFLite** → Lightweight deployment for mobile and embedded devices.  

---

## 📌 Usage Notes
- Resize inputs to **64×64** using **OpenCV INTER_NEAREST**.  
- Multiple scoring modes: objectness × class, quality emphasis, etc.  
- Ideal for **embedded experiments**, **quantization research**, and **low‑power AI applications**.  

---

## 📚 Citation

```bibtex
@software{faizaan2026uhd,
  author    = {Muhammad Faizaan},
  title     = {Ultra-lightweight-human-detection},
  year      = {2026},
  publisher = {GitHub},
  url       = {https://github.com/Muhammad-Faizaan/Ultra-lightweight-human-detection}
}
```

---

## 🔗 References
- [ESP‑DL](https://github.com/espressif/esp-dl)  
- [ESP‑WHO](https://github.com/espressif/esp-who)  
- [Ultra-Lightweight Human Detection](https://github.com/Muhammad-Faizaan/Ultra-lightweight-human-detection)  


## 💡 Why It Matters  
This project proves that **human detection doesn’t require heavyweight models**. By combining smart preprocessing with ultra‑compact networks, it achieves **usable detection at lightning speed** — perfect for IoT, robotics, and edge AI.
