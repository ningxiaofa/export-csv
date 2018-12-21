## Export_CSV
Jquery-based export table to csv file plug-in.
### api document
#### $.exportCSV(Parameter) Parameter: array
#### The array parameters have the following meanings:
```
$.exportCSV(
	[
                this, //Do not change
                '.className', //Selected table, Required, Type: string
                number, //All columns number,  Required, Type: number
                ['column-1-name', 'column-2-name', 'column-3-name', 'column-4-name',...], //Column names, Required, Type: array
                'fileNamePrefix', //The download prefix name, Required, Default: 'download', Type: string
                '-', // A date separator in a file, Default: '-', Type: string
                '_', // A time separator in a file, Default: '_', Type: string
                number // The length of random digits, Default: 6, Type: number
        ]
);
```

#### Note:
#### You can only use the ```<a>``` tag in html.
	like this:
	<a id="export_csv" style="text-decoration:none; color:black;border: solid black 1px;padding: 0 2px;" href="#">Export csv</a>
#### For details: please see the code of these files.[THANKS] 
