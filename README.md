# DNA Checker

### Feature checklist:
1. Validate input (empty, non-square, different letters, minimum length);
2. Verify if sample already exist in DB (cacheable);
3. Turn sample []string into matrix [][]string;
4. Using a concurrence pattern, we'll create 3 new rotated matrix: original, southEast (45° rotated), south (90° rotated), southWest (135° rotated));
5. Each matrix (original and rotated ones) will start a new channel to find a match using regex;
6. Calculate a maximum value to concatenate multiple lines (';' separated) to investigate the matrix faster;
