Chess16
=======

Chess 16 is a (16 by 16 square) variant of chess.
The idea is to increase the difficulty of chess for computers.
The pawns can move from 1 to 6 squares ahead on the first move.
The objective is to create a much more challenging variation
for computers which is a superset of conventional chess and contains a larger opening library.
There are 256 (16 by 16) squares compared to 64 in a normal chess game. There is a larger space to
play the game in. In total there are 192 (16 by 12) open square board spaces verses 32 (8 by 4) in a conventional
chess game.

This doesn't try to add new pieces so that it is a more conventional variant of chess. It has 1 King to maintain conventions.

There are 32 pieces per side. These pieces are: 

	4 Rooks   (R)
	4 Bishops (B)
	4 Knights (N)
	3 Queens  (Q)
	1 King    (K)
	16 Pawns  (P)

This is an alternative piece list with 1 less queen (1 is replaced by a bishop) and 5 bishops. 

	4 Rooks   (R)
	5 Bishops (B)
	4 Knights (N)
	2 Queens  (Q)
	1 King    (K)
	16 Pawns  (P)


 
Castling is also different. These will be updated later.

# Variation 16 by 8

A 16 by 8 board has this configuration. It features 64 spaces with a more compact structure.
https://github.com/singularian/chess16/blob/master/images/chess168_Board2.png


		1	2	3	4	5	6	7	8	9	10	11	12	13	14	15	16
		a	b	c	d	e	f	g	h	I	j	k	l	m	N	o	P
	8	R	R	N	N	B	B	Q	Q	K	Q	B	B	N	N	R	R
	7	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P																																
	6	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	5	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	4	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	3	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	2	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	1	R	R	N	N	B	B	Q	Q	K	Q	B	B	N	N	R	R

# Variation 16 by 16

A 16 by 16 board has this configuration
https://github.com/singularian/chess16/blob/master/images/chess16_Board2.png


		1	2	3	4	5	6	7	8	9	10	11	12	13	14	15	16
		a	b	c	d	e	f	g	h	I	j	k	l	m	N	o	P
	16	R	R	N	N	B	B	Q	Q	K	Q	B	B	N	N	R	R
	15	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	14	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	13	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	12	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	11	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	10	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	9	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	8	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	7	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	6	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	5	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	4	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	3	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.															
	2	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	1	R	R	N	N	B	B	Q	Q	K	Q	B	B	N	N	R	R



# Variation 32 by 16

A 32 by 16 board has this configuration.
Pawns can move from 1 to 14 spaces initially.


https://github.com/singularian/chess16/blob/master/images/chess16_Board2.png


		1	2	3	4	5	6	7	8	9	10	11	12	13	14	15	16
		a	b	c	d	e	f	g	h	I	j	k	l	m	N	o	P
	32	R	R	N	N	B	B	Q	Q	K	Q	B	B	N	N	R	R
	31	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	30	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	29	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	28	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	27	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	26	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	25	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	24	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	23	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	22	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	21	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	20	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	19	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	18	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	17	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	16	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	15	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.
	14	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	13	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	12	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	11	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	10	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	9	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	8	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	7	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	6	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	5	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	4	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	3	.	.	. 	.	.	.	.	.	.	.	.	.	.	.	.	.																
	2	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P	P
	1	R	R	N	N	B	B	Q	Q	K	Q	B	B	N	N	R	R


