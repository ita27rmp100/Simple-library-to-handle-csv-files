# PyCSV Library
A simple library for handling CSV files. It currently has ten functions. Look at the table below to understand the purpose of each one.
<h2>Documentation :</h2>
<table>
    <tr>
        <td>Function name :</td>
        <td>Its purpose :</td>
    </tr>
    <tr>
        <td>data(fc)</td>
        <td>Import data of csv file as an array, each element is string that holds the data of a row</td>
    </tr>
    <tr>
        <td>dataMatrix(fc)</td>
        <td>Import data of csv file with the form of matrix, each element is an array that holds the data of a row </td>
    </tr>
    <tr>
        <td>data_vr(fc)</td>
        <and>Orgnize the data of the file and display it as dictionary, the key represent the first cells of column, and the value part represent an array of the other elements of that column</td>
    </tr>
    <tr>
        <td>number_of(fc,mode)</td>
        <td>Counts the number of columns, rows and cells in a CSV file</td>
    </tr>
    <tr>
        <td>csv_files_in(folder)</td>
        <td>Return an array with the names of csv files in that folder</td>
    </tr>
    <tr>
        <td>create_and_write(fc,data)</td>
        <td>Create csv file and write in </td>
    </tr>
    <tr>
        <td>read(fc)</td>
        <td>Read the content of csv file and return the result as string not as an array like data()</td>
    </tr>
    <tr>
        <td>keyword(fc,word)</td>
        <td>Receive a keyword and then search for the row it belongs to</td>
    </tr>
    <tr>
        <td>index_cell(fc,cellContent)</td>
        <td>Return the coordinates of that cell in csv file</td>
    </tr>
    <tr>
        <td>clear(fc)</td>
        <td>Ddelete the data of csv file (data not the file itself)</td>
    </tr>
    <tr>
        <td>CSVtoXLSX(fc)</td>
        <td>Create a .xlsx copy of csv file</td>
    </tr>
</table>