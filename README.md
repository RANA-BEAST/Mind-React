# Mind-React
MindReact is a Brain-Computer Interface (BCI) system designed to detect human emotional and cognitive states using EEG signals and automate tasks based on mental states such as focus and relaxation. It leverages signal processing and machine learning to provide a smart interaction between brain activity and external devices.

🔬 Key Features
EEG Signal Acquisition using Neurochips and Arduino R4

Signal Preprocessing to extract relevant frequency bands (Alpha, Beta, etc.)

Machine Learning Classification using an SVM model to distinguish between Focus and Relax states

Real-Time Automation via Arduino for controlling appliances based on detected mental states

User-Friendly Interface built using Python for visualization and interaction

⚙️ Tech Stack
Hardware: EEG Headset, Arduino UNO R4, Relay Modules

Languages: Python, C++ (for Arduino)

Libraries: NumPy, SciPy, Scikit-learn, Matplotlib, pySerial

ML Algorithm: Support Vector Machine (SVM)

🎯 Objectives
Detect cognitive states (focus, relax) from EEG signals

Apply machine learning for accurate classification

Control home automation devices based on real-time mental state detection

🧪 Results
Achieved high accuracy in distinguishing focus vs relax states

Successfully integrated live automation (e.g., LED, fan) based on brain activity
