# ID3

# ID3 Decision Tree Implementation

This repository contains a Python implementation of the ID3 (Iterative Dichotomiser 3) algorithm, a decision tree learning method used for classification tasks in machine learning. The implementation is built from scratch to help understand the underlying logic and working of decision trees without relying on external libraries like `scikit-learn`.

## 📌 Features

* Builds a decision tree based on information gain.
* Handles categorical data.
* Simple, clean, and beginner-friendly Python code.
* Includes example dataset and prediction function.

## 🚀 Getting Started

### Prerequisites

Make sure you have Python installed (version 3.6 or above). No external libraries are required except for standard Python modules.


### Running the Code

1. Clone this repository:

   ```bash
   git clone https://github.com/pdprakruthi/id3-implementation.git
   cd id3-implementation
   ```

2. Run the main script:

   ```bash
   python main.py
   ```

This will load the dataset, build the decision tree, and test it with sample inputs.

## 🧠 How It Works

The ID3 algorithm builds the tree using a top-down, greedy approach:

1. Calculate the entropy of the dataset.
2. For each feature, calculate the information gain.
3. Choose the feature with the highest information gain as the root.
4. Recursively repeat the process for each branch until:

   * All instances belong to the same class, or
   * There are no more features to split.

## 📂 Example Output

```plaintext
Decision Tree:
Outlook?
  Sunny:
    Humidity?
      High: No
      Normal: Yes
  Overcast: Yes
  Rain:
    Wind?
      Weak: Yes
      Strong: No
```

## 📈 Future Improvements

* Add support for numerical features using threshold-based splits.
* Add pruning to reduce overfitting.
* Implement visualization for the decision tree.
* Build a simple web interface to interact with the model.

## 🤝 Contributer
-[Prakruthi P D] (https://github.com/pdprakruthi)

under the guidance of Dr Agughasi Victor Ikechukwu


Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

L
