# ionic2-sql-interface
Creating this since ionic2 rc0 removed the query interface since websql is depreciated.

Using sql.js should continue to work as browsers move away from websql

#Usage

Place file into your ionic project 
Import the file for example...

import {SqlStorage} from '../sql/sql';

Use with

var storage = new SqlStorage();

Should be a drop in replacement to get your query interface back.

#TODO

Turn into npm module and fallback to sql.js instead of websql

