# AI-Powered Cooking Agent using Gemini

An autonomous AI agent built with Python and Google's Gemini API that simulates a virtual
kitchen — receiving food orders, reasoning through cooking steps, calling kitchen tools via
function calling, managing a dynamic ingredient inventory, and verifying the final dish
against the customer's order using semantic matching.

## Features
- Dynamic ingredient inventory with real-time updates
- Kitchen tools (chop, grill, fry, toast, bake, boil, combine, serve) exposed as
  Gemini function calls
- Autonomous multi-step reasoning — no hardcoded recipes
- Structured JSON outputs for every action and verification step
- Semantic dish verification (e.g. "Veg Burger" satisfies a "Burger" order)
- Support for multiple sequential customer orders

## Tech Stack
- Python
- Google Gemini API (`google-generativeai`)
- Google Colab

## How to Run
1. Open the notebook in Google Colab
2. Add your Gemini API key as a Colab secret named `GOOGLE_API_KEY`
3. Run all cells in order

---

This task is completed as part of the workshop on **Introduction to Gemini** conducted at
**Pillai University** by **Dr. Dhiraj Aman**.
Link: [www.pillai.edu.in](https://www.pillai.edu.in)
