# Sorting Visualizer

This project provides a visualization of popular sorting algorithms implemented in C++ using the SDL2 library.

A sorting algorithm arranges the elements of a list in a specific order. While numerous sorting algorithms exist, only a few are commonly used in practical applications.

This sorting visualizer demonstrates the step-by-step execution of several of these algorithms, making it easier to understand their inner workings visually.

**Sorting Algorithms Included:**

*   Selection Sort
*   Insertion Sort
*   Bubble Sort
*   Merge Sort
*   Quick Sort
*   Heap Sort

In this visualization, all algorithms sort a list of **130 elements** in **ascending order**. You can randomize the list and choose any of the implemented sorting algorithms to observe.

**Important Note:** The visualization intentionally delays faster algorithms like Merge Sort to ensure they can be properly observed and understood during the visual representation. The visualized sorting time is therefore not an exact reflection of the algorithms' actual time complexities.

## Controls

**WARNING:** Avoid giving repetitive commands in quick succession as it may lead to latency and unexpected behavior in the visualizer. Ensure the current command's execution is complete before issuing a new one.

**Available Controls:**

*   **`0`**: Generate a new randomized list of elements.
*   **`1`**: Start the **Selection Sort** algorithm.
*   **`2`**: Start the **Insertion Sort** algorithm.
*   **`3`**: Start the **Bubble Sort** algorithm.
*   **`4`**: Start the **Merge Sort** algorithm.
*   **`5`**: Start the **Quick Sort** algorithm.
*   **`6`**: Start the **Heap Sort** algorithm.
*   **`q`**: Exit the Sorting Visualizer application.
