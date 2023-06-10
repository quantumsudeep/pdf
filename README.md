# pdf
# create pdf file using python



from reportlab.pdfgen import canvas

#create new pdf file 
pdf_file = canvas.Canvas("example1.pdf")

#add text to the file
pdf_file.drawString(72, 720, "hello world!")
pdf_file.drawString(72, 700, "free pdf document")
pdf_file.drawString(72, 680, "like|share")
pdf_file.drawString(72, 660, "subscribe")
pdf_file.drawString(72, 640, "quadcoding.com")

#save pdf file
pdf_file.save()
