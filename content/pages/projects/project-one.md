---
type: ProjectLayout
title: SaveDollar
colors: colors-a
date: '2021-10-15'
client: Awesome client
description: >-
  SaveDollar is a web-based personal finance assistant I built to manage and
  analyze my own expenses more intelligently. The app integrates AI-powered
  forecasting with financial dashboards to help users track their income,
  expenses, budgets, savings goals, and spending trends with
  ease.                                                      
featuredImage:
  type: ImageBlock
  url: 'https://assets.stackbit.com/components/images/default/default-image.png'
  altText: altText of the image
  caption: Caption of the image
  elementId: ''
media:
  type: VideoBlock
  title: Title of the video
  url: 'https://youtu.be/3ZXJRDpvRFw'
  elementId: ''
  autoplay: false
  loop: false
  muted: false
  controls: true
  aspectRatio: '16:9'
---
# 💸 SaveDollar – Intelligent Personal Finance Forecasting App

**SaveDollar** is a smart personal finance assistant designed to help users make sense of their spending, categorize transactions, and predict future expenses. Built as a capstone-style solo project, SaveDollar showcases the intersection of **machine learning**, **data science**, and **frontend engineering**. It reflects my core strength as a data-driven developer who cares about delivering **user-centered insights** with simplicity and automation.

---

## 🧠 Project Background

The idea for SaveDollar came from a real-world observation: most people, especially students and young professionals, struggle with managing their finances. While numerous apps exist, they often lack intelligent predictions and customizable insights. As a data science student passionate about **AI-driven solutions**, I wanted to create an app that not only tracks expenses but also **learns from your past behavior to forecast your future spending** — like a personal budgeting assistant that gets smarter with time.

SaveDollar was developed using a full-stack approach. The **frontend** was built using React, Tailwind CSS, and Shadcn/UI for a sleek and responsive interface, while the **backend model** was prototyped in Python using Scikit-learn to train a forecasting pipeline. The goal was to use historical transactions (imported as `.json`) and deliver dynamic forecasts with minimal user setup.

---

## ✨ Key Features

- 🔄 **Transaction Import**: Upload your personal `.json` file of bank transactions.
- 🧠 **Automated Categorization**: Transactions are sorted into standard categories like groceries, rent, transport, etc.
- 📊 **Interactive Dashboard**: Visualize spending trends across months and categories.
- 🔮 **ML-Based Forecasting**: Scikit-learn pipeline predicts your next month’s expenses by analyzing past transaction patterns.
- 🧩 **Component-Based UI**: React and Shadcn were used to build reusable, responsive, and accessible components.
- 🌙 **Dark Mode Support**: Optimized for late-night financial planning!

---

## 🔧 Tech Stack

| Layer        | Technology                                 | Purpose |
|--------------|---------------------------------------------|---------|
| Frontend     | React + Vite + TypeScript                   | Fast UI, modular component development |
| Styling      | Tailwind CSS + Shadcn UI                    | Custom styling with utility classes and prebuilt components |
| Backend (ML) | Python + Scikit-learn + Pandas              | Forecasting future expenses using regression |
| Build Tool   | Vite                                         | Lightning-fast development and production build |
| Deployment   | GitHub Pages / Vercel                       | Hosting the web app |
| File Parsing | JSON import logic in JS                     | Enables importing user transactions |

---

SaveDollar expects a `.json` file structured like this:

