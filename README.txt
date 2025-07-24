
Company Name      : CODTECH IT SOLUTIONS PVT. LTD
INTERN ID         : CTO8DH682
NAME              : M.MUTHU ARULNITHI
DOMAIN            : JAVA
START DATE        : 29 June
END DATE          : 29 July
MENTOR            : Neela Santhos Kumar

PROJECT TITLE: Neural Style Transfer (NST) in Java using Deeplearning4j

DESCRIPTION:
This Java-based project demonstrates Neural Style Transfer (NST), blending the style of a famous artwork with the content of a personal photo using deep learning.
It utilizes the pre-trained VGG16 model via Deeplearning4j (DL4J) and processes images through convolutional neural networks (CNNs) to generate artistic renditions.

PREREQUISITES:
- Java 8 or higher
- Maven build system
- Deeplearning4j and ND4J libraries
- OpenCV Java (org.bytedeco)
- content.jpg and style.jpg in the project directory

HOW TO RUN:
1. Ensure you have content.jpg and style.jpg.
2. Compile the project:
   mvn clean install
3. Run the program:
   java -cp target/your-project.jar NeuralStyleTransfer

OUTPUT:
- A new image called 'output.jpg' with style transferred output will be generated.

NOTES:
- You can adjust ITERATIONS, ALPHA, and BETA for quality.
- Ensure OpenCV is set up properly on your system.
