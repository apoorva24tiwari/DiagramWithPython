# Diagram As Code
Diagrams lets you draw the cloud system architecture in **Python code.**
Diagram as Code also allows you to track the architecture diagram changes in any version control system.


NOTE: It does not control any actual cloud resources nor does it generate cloud formation or terraform code. It is just for drawing the cloud system architecture diagrams.

**Getting Started**

It requires **Python 3.6** or higher, check your Python version first.

It uses Graphviz to render the diagram, so you need to install **Graphviz** to use diagrams. After installing graphviz (or already have it), install the diagrams.

# using pip (pip3)
$ pip install diagrams

# using pipenv
$ pipenv install diagrams

# using poetry
$ poetry add diagrams
