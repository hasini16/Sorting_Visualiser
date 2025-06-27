# Sorting Visualizer using SDL2

This project is a **graphical sorting algorithm visualizer** implemented in C++ using **SDL2** (Simple DirectMedia Layer). It provides visual representations of common sorting algorithms in real-time.

---

## ✨ Features

- Visualizes the following sorting algorithms:
  - Bubble Sort
  - Selection Sort
  - Insertion Sort
  - Merge Sort
  - Quick Sort
- Uses **SDL2 rendering** to display the sorting process.
- Highlights current elements being compared using colors:
  - Red for the currently selected element
  - Blue for the comparison target
  - Green fade-in effect on completion
- Adjustable rendering scale and speed using SDL delay

---

## 🛠️ Requirements

- **SDL2 library** installed on your system

### Install SDL2 on Ubuntu/Debian-based systems:

```bash
sudo apt update
sudo apt install libsdl2-dev
```

---

## 🧑‍💻 Build and Run

### 1. Clone the repository:

```bash
git clone https://github.com/your-username/sorting-visualizer-sdl.git
cd sorting-visualizer-sdl
```

### 2. Compile:

```bash
g++ main.cpp -o visualizer -lSDL2
```

### 3. Run:

```bash
./visualizer
```

---

## 🎮 Controls

Upon running the program, you'll see a menu in the terminal:

```
Welcome to the Sorting Visualiser -
You can visualise the following sorting types:
Bubble Sort (Press 1 and ENTER to run Bubble Sort)
Selection Sort (Press 2 and ENTER to run Selection Sort)
Insertion Sort (Press 3 and ENTER to run Insertion Sort)
Merge Sort (Press 4 and ENTER to run Merge Sort)
Quick Sort (Press 5 and ENTER to run Quick Sort)
Press -1 and ENTER to exit
```

Enter the corresponding number to visualize the desired sorting algorithm.

---

## 📊 Visualization Details

- Screen size: **600x900 pixels**
- Number of elements: **100 bars**
- Drawing scale is set with `SDL_RenderSetScale(renderer, 6, 1);`
- Real-time sorting process with animation delays (`SDL_Delay()`) for better clarity

---

## 🧹 Clean Exit

- Once the sorting is complete, a green animated fade is shown
- You can choose to run another sorting algorithm or exit by pressing `-1`

---

## 🙋‍♂️ Author

Developed by **Mamidipelli Krishna Hasini**

Feel free to contribute or raise issues!
