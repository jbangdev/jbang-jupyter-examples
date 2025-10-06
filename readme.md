# Jupyter JBang/Java Examples

Samples of various notebooks using different Jupyter Java based kernels.

> **⚠️ Note:** The JBang kernel is still under heavy development. Not all features are fully stable or working yet—expect some rough edges!


## Getting Started

### Online Access
Open online using Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jupyter-java/jupyter-java-binder/jbang?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fjupyter-java%252Fjupyter-java-examples%26urlpath%3Dlab%252Ftree%252Fjbang%252F%26branch%3Djbang%26targetPath%3Djbang)

### Local Installation
Use the following command to install the kernel locally for use in Jupyter Notebook, VSCode, IntelliJ, etc.:

```bash
jbang install-kernel@jbangdev --java 25 jbang
```

## Available Notebooks

This repository contains several example notebooks demonstrating different aspects of Java development in Jupyter:

### Core Examples
- **[basics.ipynb](basics.ipynb)** - Basic JBang examples including dependency management, JavaFaker, and markdown display

### Data Processing & Visualization
- **[dflib-echarts.ipynb](dflib-echarts.ipynb)** - DataFrame manipulation with DFLib and interactive ECharts visualization

### Database Integration
- **[jakarta-data.ipynb](jakarta-data.ipynb)** - Jakarta Data API examples with Hibernate ORM and H2 database
- **[jdbc.ipynb](jdbc.ipynb)** - Database connectivity examples using SQLite with JDBC

### AI/ML Integration
- **[langchain4j.ipynb](langchain4j.ipynb)** - AI/LLM integration examples using LangChain4j with OpenAI


## Quick Start Example

Here's a simple example to get you started with JBang in Jupyter:



```python
// Simple Hello World example
System.out.println("Hello from Jupyter Java!");

// You can also use JBang dependencies
// //DEPS org.apache.commons:commons-lang3:3.12.0
// import org.apache.commons.lang3.StringUtils;
// System.out.println(StringUtils.capitalize("hello world"));

```

## Contributing

Feel free to explore the notebooks and experiment with the examples. Each notebook is self-contained and includes detailed explanations of the concepts being demonstrated.

For more information about JBang, visit: https://jbang.dev/

For Jupyter Java kernel development, visit: https://github.com/jupyter-java

