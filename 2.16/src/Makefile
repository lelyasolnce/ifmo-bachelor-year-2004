TICKET=ticket_2.16

$(TICKET): $(TICKET).tex
	latex $(TICKET).tex

pdf: $(TICKET)
	pdflatex $(TICKET).tex
	mv $(TICKET).pdf ../bin
	evince ../bin/$(TICKET).pdf
