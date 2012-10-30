all: merge1.xln

merge1.xln:
	gerbmerge --no-trim-gerber --no-trim-excellon layout1.cfg layout1.def

view1:
	gerbv merge1.* &

clean:
	-rm -f merge1.* toollist.* placement.*
