# Export_CSV
Jquery-based export table to csv file plug-in.
# api document
## Call parameters are as follows:
## $.exportCSV Parameter: array
## The array parameters have the following meanings:
$.exportCSV(
		    [
                this, //do not change
                '.className', //seleted table required
                number, //all columns number  required 
                ['column-1-name', 'column-2-name', 'column-3-name', 'column-4-name',...], //column names required
                'fileNamePrefix', //The download prefix name required Default: 'download'
                '-', // A date separator in a file Default: '-'
                '_', // A time separator in a file Default: '_'
                number // The length of random digits Default: 6
        ]
);
