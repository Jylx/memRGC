# memrgc

Memrgc is a tool for compression genome sequence. The program is written in C++11 and tested on Red Hat Enterprise Linux 7.5 (64 bit). 

## Download & Compile

	git clone https://github.com/yuansliu/memrgc.git
	cd memrgc
	make

## Usage

	./memrgc &lt;e|d> -m &lt;mode> -r &lt;reference> -t &lt;target> -o &lt;output> [options]

	-m  	mode; 'file' compress a single file; 'genome' compress a genome
	-r  	reference file or genome
	-t  	target file or genome
	-o  	the output file
	-f  	use to set the file name; each line contain two file names
	-n  	the number of threads
	-h  	print help message

## Contacts
If any bugs during you run our code, please email to <Yuansheng.Liu@uts.edu.au>
