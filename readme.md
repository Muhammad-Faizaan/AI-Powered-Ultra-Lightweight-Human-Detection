
# Ultra‑Lightweight Human Detection

### 🚀 What This Project Is  
A streamlined deep learning solution for **human detection** that prioritizes **speed, efficiency, and deployability**. Unlike heavy object detection frameworks, this project focuses on **tiny models** that run on constrained hardware while still delivering reliable results.

---

## ✨ Features
- **Compact Models**: Variants from *Ront* (0.13M params) to *Large* (30M params).  
- **Fast Inference**: Latency as low as **0.24 ms** on Core i9 CPUs.  
- **Flexible Input**: Supports RGB, YUV422, luminance‑only, ternarized, and binarized formats.  
- **Embedded Ready**: Optimized for ONNX, TFLite, and ESP‑DL (ESP32‑S3).  
- **Custom Dataset**: Built from MS‑COCO but refined for higher quality — ensuring meaningful detection beyond benchmark scores.  

---

## 📊 Model Options
Choose the right balance of **speed vs. accuracy**:

| Variant | Params | Latency (Core i9) | File Size |
|---------|--------|-------------------|-----------|
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

## ⚙️ Deployment
- **ONNX** → General inference on desktop/server.  
- **ESP‑DL INT8** → Quantized models for ESP32 hardware.  
- **TFLite** → Lightweight deployment for mobile/embedded devices.  

---

## 📌 Usage Notes
- Resize input images to **64×64** using **OpenCV INTER_NEAREST**.  
- Multiple scoring modes available (objectness × class, quality emphasis, etc.).  
- Ideal for **embedded experiments**, **quantization research**, and **low‑power AI applications**.  

---

## 📚 Citation
If you use this project, please cite:

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
- [Ultralightweight-Human-Detection]((https://github.com/Muhammad-Faizaan/Ultra-lightweight-human-detection))  

---

## 💡 Why It Matters
This project proves that **human detection doesn’t need heavyweight models**. By combining smart preprocessing with ultra‑compact networks, you can achieve **usable detection at lightning speed** — perfect for IoT, robotics, and edge AI.
