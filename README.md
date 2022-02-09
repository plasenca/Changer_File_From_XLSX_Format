# Changer File From XLSX Format
It's a script totally in python which change an exisisting file name to another name which is extracted from a xlsx file.

## Pay Attenttion
- The path have to be indicated in the first argument on the command line.
- Each file must have the same name as each column name called 'CÓDIGO CATALOGO'
- The file's sheet must have the name 'DATA'
- The '.xlsx' extension must just have 3 columns ["CODIGO INTERNO","CÓDIGO CATALOGO","MARCA"]

## Script Running:

- Script takes 2 parameters from the command line:

    - The first parameter is the path of xlsx file.
    - The second parameter is the path of the files will be changed.
    ![script parameters](https://github.com/plasenca/Changer_File_From_XLSX_Format/blob/master/script%20parameters.png)

- Showing the exisisting file from the choosed directory
![files_to](https://github.com/plasenca/Changer_File_From_XLSX_Format/blob/master/files_to.png)

- Showing the order of the columns of the xlsx file
![columns_xlsx](https://github.com/plasenca/Changer_File_From_XLSX_Format/blob/master/order_columns.png)

- Showing the return of the script
![return_script](https://github.com/plasenca/changer_file_from_xlsx_format/blob/master/executing.png)