# Marble-Clock-Numerals
An exploration of digital display numerals focused on efficiency. 

![Numerals]([path/to/your/image.svg](https://raw.githubusercontent.com/PancakeLegend/Marble-Clock-Numerals/refs/heads/main/Marble%20Clock%20Numeral%20Design.svg)



A response to [design](https://www.youtube.com/watch?v=aYX8qytpilQ) by Strange Inventions (Jens Maker Adventures)

### OP Design

0-1 = 0 moves within, 7 put to bank

1-2 = 1 move within, 6 pulled from bank

2-3 = 1 move within

3-4 = 1 move within, 2 put to bank

4-5 = 1 move within, 2 pulled from bank

5-6 = 0 moves within, 1 pulled from bank

6-7 = 1 move within, 5 put to bank

7-8 = 0 moves within, 6 pulled from bank

8-9 = 0 moves within, 1 put to bank

9-0 = 1 move within


= 36 total operations, 30 put/pull

### New Design

0-1 = 6 moves within

1-2 = 2 moves within

2-3 = 2 moves within

3-4 = 4 moves within

4-5 = 1 move within, 2 pulled from bank

5-6 = 2 moves within

6-7 = 2 move within, 3 put to bank

7-8 = 0 moves within, 4 pulled from bank

8-9 = 1 move within, 1 put to bank 

9-0 = 2 moves within, 2 put to to bank 


= 34 total operations, 12 put/pull


New design results in 2 fewer operations overall, but reduces the put and pull from the bank by 18 operations.


Overall the reduction in total operations only goes down by 2, from 36 down to 34 in a complete cycle. However, within that set I've reduced the put/pull operations to and from the bank from 30 down to 12. This means that the majority of moves pick up a bearing and move it only a few pixels away. If including optimised bank locations near the numerals, I expect the total movement travel to be reduced to less than 10% of the original design.

bit dot ly / Clock-Numeral-SVG

