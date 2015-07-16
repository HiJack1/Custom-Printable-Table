# Custom-Printable-Table
Is there a way to make to default not print into the region of the header/footer? And yeah, it is: double-wopper (ehh .. wrapper) is the answer - make the default printable believe it has less printable space by wrapping the given pageFormat into one that returns a adjusted getImageableHeight/Y.
