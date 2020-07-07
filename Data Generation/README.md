
Execute the script files according to this sequence:

1). Extract data from DBLP. Use DBLP.xml file (link mentioned in code). Use portion of this xml file, and parse it to get the dataframe with all required metadata fields

2). Generate new data: First SAVE from your template the first page (or the relevant page which has metadata), then convert it to docx file. Place both the docx and PDF file 
in the folder containing 'Generating new data.ipynb' and 'Convert docx to PDFs.ipynb' . Check the layout of the docx file and replace the data (e.g author name, title etc) 
with data from your dataframe. This will generate docx files for new generated data 

3). Convert docx files to PDFs. 'Convert docx to PDFs.ipynb' will automatically create new folder 'PDFs'. Place 'Convert PDFs to Images and Resize.ipynb' and 
'Annotating Generated data.ipynb' in this folder. 

4). Then Convert PDFs to images and resize them

5). Annotate images. If image is not annotated, you may need to check whether the bounding boxes list, coordinates_author list, coordinates_title list and so on are empyty or not. 