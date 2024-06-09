# Interactive Photo Gallery

This project is an interactive photo gallery built using HTML, CSS, and JavaScript. It showcases an elegant and responsive design with smooth hover interactions and transitions. also it includes other challenges

## Features

- **Responsive Design**: Adapts seamlessly to different screen sizes.
- **Hover Interactions**: Images grayscale and blur with smooth transitions on hover.
- **Cross-Browser Compatibility**: Works consistently across modern web browsers.

## Getting Started

### Prerequisites

- Web browser (Chrome, Firefox, Safari, etc.)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/MugAbdoul/interactive-photo-gallery.git
2. Navigate to the project directory:
   ```sh
   cd interactive-photo-gallery
4. Open `index.html` in your web browser to view the gallery.

## Coding Challenges

### Challenge 1: Array Manipulation

Given an array of integers and a target sum, determine if there exists a contiguous subarray within the array that sums up to the target. Return true if such a subarray exists, otherwise return false.

#### Example

```plaintext
Input: arr = [4, 2, 7, 1, 9, 5], target = 17
Output: true
Explanation: The subarray [7, 1, 9] sums up to 17, which is equal to the target.
```
##### Solution
See **Challenges/arrayMap.js**.

### Challenge 2: String Transformation
Given a string, transform it based on the following rules:

- If the length of the string is divisible by 3, reverse the entire string.
- If the length of the string is divisible by 5, replace each character with its ASCII code.
- If the length of the string is divisible by both 3 and 5 (i.e., divisible by 15), perform both operations in the order specified above.
  
#### Examples

```plaintext
Input: "Pizza"
Output: "80 105 122 122 97"
Explanation: The length of the string is 5, which is divisible by 5 but not by 3 or 15. Therefore, each character is replaced by its ASCII code, resulting in "80 105 122 122 97".
```

##### Solution
See **Challenges/stringTransform.js**.
