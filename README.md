# 🩺 Secure Medical AI: Pneumonia Detection
This AI analyzes Chest X-rays using a hardened ResNet18 model to detect Pneumonia while resisting adversarial attacks.

## 📊 Results
<table>
  <tr>
    <td><b>Normal Case</b></td>
    <td><b>Pneumonia Case</b></td>
  </tr>
  <tr>
    <td><img src="normal.png" width="400"></td>
    <td><img src="pneumonia.png" width="400"></td>
  </tr>
</table>

## 🛡️ Security Features
- **Adversarial Hardening:** Trained against FGSM noise.
- **Strict Threshold:** Classification set at 0.8 to reduce false positives.

## 🚀 How to Run
1. Clone this repo.
2. Install dependencies: `pip install -r requirements.txt`
3. Download the model weights [HERE](https://drive.google.com/file/d/1wxqxwNcRci5zV8LF_P-aSfJ0b4_rn-La/view?usp=drive_link).
4. Run the app: `streamlit run app.py`
