Chess16
=======

Chess 16 is a (16 by 16) variant of chess.
The idea is to increase the difficulty of chess for computers.
The pawns can move from 1 to 6 squares ahead on the first move.
The objective is to create a much more challenging variation
for computers which is a superset of conventional chess and contains a larger opening library.
There are 256 (16 by 16) squares compared to 64 in a normal chess game. There is a larger space to
play the game in.

There are 32 pieces per side. These pieces are: 

	4 Rooks   (R)
	4 Bishops (B)
	4 Knights (N)
	3 Queens  (Q)
	1 King    (K)
	16 Pawns  (P)

 
Castling is also different. These will be updated later.

A 16 by 16 board has this configuration
https://github.com/singularian/chess16/blob/master/images/chess16_Board2.png


		1	2	3	4	5	6	7	8	9	10	11	12	13	14	15	16
		a	b	c	d	e	f	g	h	I	j	k	l	m	N	o	P
	16	R	R	N	N	B	B	Q	Q	K	Q	B	B	N	N	R	R
	15	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	14																
	13																
	12																
	11																
	10																
	9																
	8																
	7																
	6																
	5																
	4																
	3																
	2	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	1	R	R	N	N	B	B	Q	Q	K	Q	B	B	N	N	R	R

