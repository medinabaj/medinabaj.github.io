---
title: "🎓 Master Thesis - Differential Growth Curve Analysis "
layout: post
date: 2023-07-24
tag:
- R
- Gaussian Process
- Research
- Statistical Modeling
- Bayesian Hypothes Testing
#image: https://borhenryk.github.io/henryk_githubpage/assets/images/gan.png
headerImage: true
projects: true
hidden: false # don't count this post in blog pagination
description: "R Package for Differential Growth Curve Analysis"
category: project
author: medinabajramovic
externalLink: false
---

# 🎓 Master Thesis - Differential Growth Curve Analysis 
**Institution:** Ludwig-Maximilians-Universität München, Munich, Germany 📍
**Duration:** March 2023 - Present ⏳

## 🌍 Global Health Crisis: Antibiotic-Resistant Bacteria 
In recent years, antibiotic-resistant bacteria have emerged as a serious global public health problem, reducing our ability to effectively treat diseases and infections. As a result, we are seeing severe disease progression, longer hospital stays and increased mortality.

Pathogens such as Salmonella and Campylobacter, which have shown an increasing tendency to become resistant to antibiotics, have been identified as leading causes of foodborne illness worldwide.

## 💡 Our Approach: Growth Curve Analysis 
One way to determine bacterial resistance is to analyse their growth under both normal and antibiotic-induced conditions. Antibiotic-resistant bacteria will continue to grow even under induced conditions, whereas effective antibiotics will result in non-growing curves. Traditionally, growth curves are modelled using assumptions about the shape of the curve, such as sigmoidal functions. However, this limits the ability to model non-growing curves or curves that don't follow the classic S-shape. 

Our approach is therefore to use Gaussian processes to model growth curves, which do not make any assumptions about the underlying curves, allowing for more flexibility. However, these approaches have mainly been implemented in Python. Therefore, as part of my master's thesis, I am developing an R package called "degrowth" for differential growth curve analysis.

## 🧪 Bayesian Hypothesis Testing and Bayes Factor
Another challenge is the need for differential testing of growth curves. This involves comparing growth patterns under ideal and chemically induced conditions and helps to identify significant differences between curves. However, due to the complexity of growth data, differential testing can be challenging. To overcome this hurdle, we are using Bayesian hypothesis testing through Bayes Factor and Permuted Bayes Factor, both of which will be included in the package.

## 🤖 On Gaussian Processes 
Notably, Gaussian processes are a key component of our analysis. Gaussian processes (GPs) are a powerful supervised learning technique. In a nutshell, they allow us to define a prior over functions and use the observed data to update our prior beliefs about the likely outputs for new inputs. GPs are particularly useful for regression problems and excel when you have prior knowledge about the characteristics of the function.

## 🚀 Skills and Future Developments 
This project draws on a range of skills including statistical modelling, computer science, biostatistics, scientific analysis, Python and R. The 'degrowth' package, which aims to create a powerful and user-friendly tool for analysing growth curves with differential effects, is expected to be available in November 2023. Stay tuned for this exciting development!
