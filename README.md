# Sorting Visualizer

## Overview
Sorting Visualizer is a Java-based application that provides a graphical representation of various sorting algorithms. This tool allows users to visualize the step-by-step sorting process for algorithms such as Bubble Sort, Insertion Sort, Selection Sort, and Quick Sort.

## Files
*Main.java*: The main class responsible for starting the sorting visualizer.

*Frame.java*: Defines the main JFrame for the application, setting up the GUI components and initializing the sorting panel.

*ButtonModel.java*: Custom button model to handle button behavior.

*BubbleSort.java*, *InsertionSort.java*, *SelectionSort.java*, *QuickSort.java*: Implementations of different sorting algorithms.

SortingPanel.java: The JPanel where the sorting visualization occurs, including buttons for controlling the visualization.

## How to Run
- Compile and run the Main.java file to launch the Sorting Visualizer. 
- The graphical interface will appear, allowing users to choose a sorting algorithm and visualize its operation on a randomly generated array.

## Usage
- Click the "start" button to initiate the sorting visualization.
- Choose a sorting algorithm by clicking the respective algorithm button (Bubble, Insertion, Selection, Quick).
- Click the "reset" button to reset the array and stop the current visualization.
- The visualization uses different colors to highlight elements involved in the sorting process.

## Notes
- The program utilizes Java Swing for GUI components.
- Each sorting algorithm is implemented in a separate class to enhance modularity.
- Visualization colors help users track elements during the sorting process.
