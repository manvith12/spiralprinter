# Spiral Grid Pattern

This program creates a square grid (like a chessboard) and fills it with a spiral pattern. It then prints the grid using stars (`*`) and spaces.

## Overview

1. **Ask for a Number**: The program starts by asking for a number, `N`. This number determines the size of the grid. For example, if you enter `5`, the grid will be `5 rows by 5 columns`.

2. **Create the Grid**: The program initializes an empty grid with `N` rows and `N` columns. Initially, all spots in the grid are set to `0`.

3. **Draw the Spiral**:
    - The program starts at the top-left corner of the grid.
    - It moves right, then down, then left, and then up, creating a spiral shape.
    - Each time it moves, it changes the `0` in the grid to a `1` to mark the path of the spiral.

4. **Print the Grid**:
    - The program iterates through each spot in the grid.
    - If the spot has a `1`, it prints a space (` `).
    - If the spot has a `0`, it prints a star (`*`).

## Example

If you enter `50`, the program will create a `50x50` grid and fill it with a spiral pattern. The output will look like this:

![image](https://github-production-user-asset-6210df.s3.amazonaws.com/67535496/383272817-ec18ae5d-146f-46ba-9226-80f775c52011.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20241105%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241105T183707Z&X-Amz-Expires=300&X-Amz-Signature=31f131b062eb8c97aff89dd4f920d038675f18981ed2aea15cf60c831617bcef&X-Amz-SignedHeaders=host)
