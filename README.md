# ECE385-Rough-Draft
ECE385 Final Project by Liu Jingcheng and Zhou Juncheng
Here is a rough draft which we have not sorted out, But I'm sure it can be applied on your FPGA.

3D Cube Visualization
We implement a 3D magic cube on FPGA. The cube can be visualized on a VGA monitor and is controlled by a keyboard. The frame clk is about 60 Hz, so you may see a smoothly rotating cube.
Our cube is able to switch colors like a real magic cube. We have many operations to do it, you can have a try.

Basic operations
If you can play magic cube, I believe that you are not more familiar with our operations. R, R', L, L', U, U', D, D', F, F', (B,B'), M, corresponding to O, L, H, Y, U, I, M, N, K, J and P.
If you don't know how to play a magic cube. OK, let me explain it. R means right slab rotate 90 degree clockwise, R' means 90 degree counterclockwise. So left operations are R-right, L-left, U-up, D-down, F-front, B-back. In our design, we simplified it a little, we use up and down, left and right rotation to replace clockwise and counterclockwise. Really interesting.
