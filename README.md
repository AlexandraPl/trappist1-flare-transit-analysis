# TRAPPIST-1 Flare–Transit Analysis

This repository contains the Python code and analysis framework developed as part of an M.Sc. thesis project.  
The project investigates the effect of stellar flares on exoplanet transit light curves and the reliability of transmission spectra, with a focus on the TRAPPIST-1 system observed by JWST/NIRSpec.

---

## 📄 Project Overview
The code implements a simulation-like framework performing:
- Data preprocessing and flare identification  
- Synthetic transit injection (achromatic and chromatic cases)  
- Flare modeling based on Tovar Mendoza et al. (2022)  
- MCMC parameter estimation using `emcee`  
- Gaussian Process noise modeling using `george`  
- Bayesian model comparison with nested sampling (`ultranest`)


---

## 🧠 Development Notes
This code was written in **Python 3.11** using standard scientific libraries:  
`numpy`, `scipy`, `matplotlib`, `batman`, `emcee`, `george`, and `ultranest`.

Parts of the code were written with the assistance of **LLMs** for programming and documentation:
- [ChatGPT (OpenAI, GPT-5)](https://openai.com/chatgpt)
- [Claude Sonnet 4.5 (Anthropic), via GitHub Copilot](https://www.anthropic.com/claude/sonnet)

All code was manually reviewed, tested, and validated by the author.
