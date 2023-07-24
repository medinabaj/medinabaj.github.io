<!DOCTYPE html>
<html>
<head>
    <title>Master Thesis - Differential Growth Curve Analysis</title>
    <style>
        .highlight {
            color: #ff6347; /* Tomato color for highlights */
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>📚 Master Thesis - Differential Growth Curve Analysis 📈</h1>
    <p><strong>Institution:</strong> Ludwig-Maximilians-Universität München, Munich, Germany 📍</p>
    <p><strong>Duration:</strong> March 2023 - Present ⏳</p>

    <h2>🌍 Global Health Crisis: Antibiotic-Resistant Bacteria 🌍</h2>
    <p>In recent years, antibiotic-resistant bacteria have emerged as a serious global public health issue, reducing our ability to effectively treat diseases and infections. Consequently, we witness severe disease progression, prolonged hospital stays, and increased mortality rates. Major health organizations like the World Health Organization and the Centers for Disease Control and Prevention have categorized the research and development in this field as high-priority. 🚑</p>
    <p>Pathogens, including Salmonella and Campylobacter, which have shown an increasing tendency for antibiotic resistance, have been identified as leading causes of foodborne illnesses worldwide. Such bacteria are under study in the StressRegNet project within the research network 'New strategies against multi-resistant pathogens by means of digital networking' (bayresq.net). The project employs chemogenomic approaches to examine bacterial stress responses and virulence signaling pathways during infection. 🦠</p>

    <h2>💡 Our Approach: Growth Curve Analysis 💡</h2>
    <p>One method to determine bacterial resistance is by analyzing their growth under both normal and antibiotic-induced conditions. Antibiotic-resistant bacteria will continue to grow even under induced conditions, while effective antibiotics will result in non-growing curves. Traditionally, growth curves are modelled using assumptions about the curve's shape, like sigmoidal functions. However, this limits the ability to model non-growing curves or curves that don't follow the classic S-shape. 📉</p>
    <p>Our approach, therefore, is to employ Gaussian Processes to model growth curves, which do not make any assumptions about the underlying curves, allowing for more flexibility. However, these approaches have predominantly been implemented in Python. Hence, as part of my master thesis, I am developing an R package called "degrowth" for differential growth curve analysis. 📊</p>
  
    <h2>🧪 Bayesian Hypothesis Testing and Bayes Factor 🧪</h2>
    <p>Another challenge is the need for differential testing for growth curves. This involves comparing growth patterns under ideal and chemically induced conditions and helps identify significant differences between curves. However, due to the complexity of growth data, differential testing can be challenging. To overcome this hurdle, we are utilizing Bayesian hypothesis testing through Bayes Factor and permuted Bayes Factor, both of which will be integrated into the "degrowth" package. 🧮</p>

    <h2>🤖 On Gaussian Processes 🤖</h2>
    <p>Of note, Gaussian Processes are a key component of our analysis. Gaussian Processes (GPs) are a powerful supervised learning method 🎓. In a nutshell, they allow us to define a prior over functions and use the observed data to update our prior beliefs about the probable outputs for new inputs. GPs are particularly useful for regression problems, and excel when you have prior knowledge about the function's characteristics. 👀</p>

    <h2>🚀 Skills and Future Developments 🚀</h2>
    <p>This project involves leveraging a range of skills, including Statistical Modeling, Computer Science, Biostatistics, Scientific Analysis, Python, and R. The "degrowth" package, which aims to create a powerful and user-friendly tool for analyzing growth curves with differential effects, is expected to be available in November 2023. Stay tuned for this exciting development! 📆</p>

</body>
</html>

