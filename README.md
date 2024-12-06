# Will TuringBots Replace Human Software Developers?

## Overview
This project explores the potential of AI assistants and Generative AI platforms to replace human software developers. By leveraging Big Data Analytics using PySpark and SparkML, we analyzed 1.36 TiB of GitHub repository data, including metadata like commits, file contents, languages, and licenses, to uncover key insights and evaluate AI's capabilities and limitations in the software development domain.

## Objectives
- Analyze GitHub repository data to identify trends in programming language usage and licensing.
- Evaluate the impact of AI-assisted tools on software development productivity.
- Examine the role of AI technologies in augmenting human capabilities.

## Key Findings
- **AI Augments, Not Replaces:** AI assistants improve efficiency and productivity but cannot replace human creativity, problem-solving, and domain expertise.
- **Popular Programming Languages:** Python, JavaScript, HTML, CSS, and C++ dominate GitHub, indicating a strong focus on web development, AI, and data science.
- **Licensing Trends:** MIT license is the most prevalent, especially for Python and JavaScript repositories.
- **Big Tech Influence:** Technologies like VS Code (Microsoft) and React-Native (Meta) highlight the contributions of large tech companies to open-source ecosystems.

## Methodology
1. **Data Collection and Cleaning:**
   - Initial dataset of 26,538,161 records spanning 2008-2023.
   - Removed irrelevant columns and filtered data for meaningful insights.
2. **Big Data Analysis:**
   - Utilized PySpark for processing 1.36 TiB of data efficiently.
   - Conducted Linear Hashing (LSH) and sentiment analysis on commit messages and repository metadata.
3. **Insights Extraction:**
   - Identified key technologies and frameworks associated with AI and Data Science projects.
   - Analyzed commit trends to understand developer motivations.

## Insights
- **AI and Data Science Technologies:** Python, TensorFlow, Apache Spark, and Kubernetes are central to AI-driven projects.
- **Commit Trends:** Updates to README files and initial commits are the most common, reflecting the importance of documentation and project initialization.
- **Decline in GitHub Popularity:** Emerging platforms like GitLab and Bitbucket are diversifying developer preferences.

## Recommendations
1. **Leverage AI as an Assistant:** Use AI tools to complement human efforts rather than replacing them entirely.
2. **Address Ethical Concerns:** Maintain human oversight to mitigate biases and ensure ethical coding practices.
3. **Focus on Collaborative Development:** Emphasize synergy between AI capabilities and human expertise to achieve optimal outcomes.

## Conclusion
AI-assisted tools are revolutionizing software development by enhancing productivity and facilitating learning. However, human creativity and problem-solving remain irreplaceable. By fostering collaboration between AI and developers, the software industry can achieve unprecedented innovation and efficiency.

---

## How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/ArushiMakraria/Turinbots-replacing-humans.git
   ```
2. Explore the analysis notebooks for detailed steps and methodologies.
3. Use the included scripts to replicate data processing and insights generation.

For questions or feedback, feel free to reach out!
