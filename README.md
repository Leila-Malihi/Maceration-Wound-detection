# Maceration-Wound-detection
# MobileNetV2 Transfer Learning for Binary Image Classification

This repository contains code for training and evaluating a MobileNetV2 model using transfer learning for binary image classification. The model is trained on a dataset of cropped images of wounds categorized as either maceration or another type.

## Project Structure

- **Scripts**: Python scripts used for training (`train_mobilenetv2.py`) and evaluating (`evaluate_mobilenetv2.py`) the model.
- **Data**: Dataset directory (`maceration-cropped double-checked-splitted/`) containing subdirectories for training, validation, and test data splits.
- **Saved Models**: Directory (`saved_models/`) where the best model checkpoint (`Mobilenetv2-best_model.h5`) is saved during training.

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib
- Scikit-learn

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mobilenetv2-binary-classification.git
   cd mobilenetv2-binary-classification


\subsection*{Requirements}
\begin{itemize}
    \item Python 3.x
    \item TensorFlow 2.x
    \item NumPy
    \item Matplotlib
    \item Scikit-learn
\end{itemize}

\section*{Installation}
\begin{enumerate}
    \item Clone the repository:
    \begin{verbatim}
    git clone https://github.com/your-username/mobilenetv2-binary-classification.git
    cd mobilenetv2-binary-classification
    \end{verbatim}
    
    \item Install dependencies:
    \begin{verbatim}
    pip install -r requirements.txt
    \end{verbatim}
\end{enumerate}

\section*{Usage}

\subsection*{Training}
\begin{itemize}
    \item Run \texttt{train\_mobilenetv2.py} to train the MobileNetV2 model:
    \begin{verbatim}
    python train_mobilenetv2.py
    \end{verbatim}
    
    \item The best model based on validation accuracy will be saved as \texttt{Mobilenetv2-best\_model.h5} in the \texttt{saved\_models/} directory.
\end{itemize}

\subsection*{Evaluation}
\begin{itemize}
    \item Run \texttt{evaluate\_mobilenetv2.py} to evaluate the trained model on the test set:
    \begin{verbatim}
    python evaluate_mobilenetv2.py
    \end{verbatim}
    
    \item Evaluation metrics such as test accuracy, precision, recall, and F1-score will be displayed.
\end{itemize}

\section*{Results}
\begin{itemize}
    \item \textbf{Training Time}: Approximately X hours
    \item \textbf{Validation Time}: Approximately Y minutes
    \item \textbf{Test Accuracy}: 78.1\%
    \item \textbf{Precision}: 60\%
    \item \textbf{Recall}: 55.5\%
    \item \textbf{F1-score}: Calculated as $2 \times (\text{precision} \times \text{recall}) / (\text{precision} + \text{recall})$
\end{itemize}

\section*{Acknowledgments}
\begin{itemize}
    \item The base MobileNetV2 model is pre-trained on ImageNet.
    \item Dataset used: [Provide dataset source or description if applicable]
\end{itemize}

\section*{License}
This project is licensed under the MIT License - see the LICENSE file for details.

\end{document}
