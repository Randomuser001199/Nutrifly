# 🥗 Nutrifly

Nutrifly is a free, science-backed diet planning web application that helps users generate personalized 7-day meal plans based on their health profile and fitness goals. The application requires **no sign up**, making it simple and accessible for anyone to use.

Built with **React** and **Vite**, Nutrifly offers a modern, responsive, and user friendly experience across all devices.

---

## ✨ Features

- 🥗 Generate personalized 7-day diet plans
- 📊 Science-backed nutrition recommendations
- 📄 Download complete diet plans as multi-page PDFs
- 🎨 Premium theme selection with persistent preferences
- 📱 Fully responsive design for desktop, tablet, and mobile
- ⚡ Fast and lightweight React + Vite application
- 🔒 No account or sign-up required

---

## 🧬 Science Behind Nutrifly

Nutrifly generates personalized meal plans using established nutritional formulas that estimate your daily calorie requirements based on your body measurements, age, activity level, and fitness goals.

### 1. Basal Metabolic Rate (BMR)

The application first calculates your **Basal Metabolic Rate (BMR)** using the **Mifflin St Jeor Equation**, one of the most widely accepted formulas for estimating the number of calories your body burns at complete rest.

**For Men**

```text
BMR = (10 × Weight in kg) + (6.25 × Height in cm) − (5 × Age) + 5
```

**For Women**

```text
BMR = (10 × Weight in kg) + (6.25 × Height in cm) − (5 × Age) − 161
```

BMR represents the calories your body needs each day to perform essential life-sustaining functions such as:

- ❤️ Heartbeat
- 🫁 Breathing
- 🧠 Brain activity
- 🌡️ Maintaining body temperature
- 🩸 Blood circulation

---

### 2. Total Daily Energy Expenditure (TDEE)

Since people perform daily activities beyond resting, NutriNavigator estimates **Total Daily Energy Expenditure (TDEE)** by multiplying the calculated BMR with a standard activity multiplier.

| Activity Level | Multiplier |
|----------------|-----------:|
| Sedentary | 1.20 |
| Lightly Active | 1.375 |
| Moderately Active | 1.55 |
| Very Active | 1.725 |
| Extra Active | 1.90 |

```text
TDEE = BMR × Activity Multiplier
```

TDEE estimates the total number of calories required each day to maintain your current body weight.

---

### 3. Personalized Calorie Goals

After calculating your TDEE, NutriNavigator adjusts your daily calorie target according to your selected fitness objective:

- 📉 **Weight Loss** — Creates a calorie deficit to promote gradual fat loss.
- ⚖️ **Weight Maintenance** — Matches your estimated daily calorie requirement.
- 💪 **Weight / Muscle Gain** — Creates a calorie surplus to support healthy weight and muscle gain.

The calculated calorie target is then used to generate a balanced **7-day personalized meal plan** with appropriate nutritional distribution and portion sizes.

> **Note:** The generated plans are intended for general wellness and educational purposes. Individual nutritional requirements may vary depending on medical conditions, medications, and other health factors. Consult a qualified healthcare professional or registered dietitian before making significant dietary changes.

---

## 🛠️ Tech Stack

- React
- Vite
- JavaScript
- HTML5
- CSS3
- jsPDF

---

## 👥 Team Members

- Shivam Singh
- Sameer Vajir Khan
- Sairaj
- Karan

---

## 📦 Installation

Clone the repository and install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the URL displayed in the terminal (typically):

```
http://localhost:5173
```

---

## 🏗️ Production Build

Create a production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

---

## 🚀 Deployment

### Deploy to Vercel

Install the Vercel CLI:

```bash
npm install -g vercel
```

Deploy the application:

```bash
vercel
```

Follow the prompts to complete the deployment.

---

## 📄 License

This project is intended for educational and personal use.

---

## ❤️ Acknowledgements

Nutrifly is designed to make healthy eating more accessible through science backed nutritional recommendations, evidence-based calorie estimation, and a clean, modern user experience.