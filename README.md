def generate_detailed_github_intro(
    name,
    title,
    bio,
    skills,
    tools,
    projects,
    contributions,
    learning_goals,
    contact_info,
    github_url,
):
    intro = f"""
# 👋 Hi, I'm {name}!

Welcome to my GitHub profile! I'm a passionate **{title}** dedicated to exploring innovative solutions, building impactful projects, and contributing to open-source communities.

---

## 👨‍💻 About Me

{bio}

---

## 🛠️ Skills and Tools

### 💻 Technical Skills:
{", ".join(skills)}

### 🧰 Tools and Technologies:
{", ".join(tools)}

---

## 🌟 Portfolio Highlights

Here are a few notable projects I've worked on:

{projects}

---

## 🤝 Open Source Contributions

{contributions}

---

## 🚀 Currently Learning

{learning_goals}

---

## 📬 Let's Connect

- 📂 GitHub: [{name}]({github_url})
- 📧 Email: {contact_info}
- 💼 LinkedIn: [My LinkedIn](#) (replace this link with yours)

Feel free to explore my repositories, star the ones you like, and let’s collaborate on exciting projects! ✨
"""
    return intro


# Example inputs
name = "John Doe"
title = "Data Scientist | Machine Learning Engineer | Open Source Enthusiast"
bio = (
    "I specialize in using data-driven approaches to solve real-world problems. "
    "With a strong background in Python, machine learning, and data visualization, I enjoy creating scalable solutions."
)
skills = [
    "Python",
    "R",
    "Machine Learning",
    "Deep Learning",
    "Data Analysis",
    "SQL",
]
tools = [
    "Jupyter Notebook",
    "TensorFlow",
    "Scikit-learn",
    "Power BI",
    "Tableau",
    "Git",
]
projects = """
- **Customer Churn Prediction**: Developed a machine learning model to predict customer retention, achieving 95% accuracy.  
- **Stock Price Forecasting**: Built a time-series analysis pipeline to forecast stock trends with ARIMA models.  
- **Sentiment Analysis**: Analyzed product reviews using NLP techniques to extract actionable insights.  
"""
contributions = """
- Contributed to the [Scikit-learn](https://github.com/scikit-learn/scikit-learn) repository by improving documentation.  
- Submitted bug fixes and feature enhancements to popular Python libraries like Pandas and NumPy.  
- Actively participate in Hacktoberfest, contributing to beginner-friendly repositories.  
"""
learning_goals = (
    "Currently exploring advanced topics in reinforcement learning, "
    "MLOps best practices, and deploying scalable AI solutions on cloud platforms."
)
contact_info = "john.doe@example.com"
github_url = "https://github.com/johndoe"

# Generate and print the detailed intro
print(
    generate_detailed_github_intro(
        name,
        title,
        bio,
        skills,
        tools,
        projects,
        contributions,
        learning_goals,
        contact_info,
        github_url,
    )
)

