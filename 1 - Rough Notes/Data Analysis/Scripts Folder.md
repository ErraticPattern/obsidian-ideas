+ `init`
+ `setpath`
+ `config`
+ `master`
+ `rec`
	+ `assign_participant_id`
	+ `send_email`
+ `beh`
	+ `load_hexaco`
	+ `load_bisbas`
+ `bids`
	+ `convert2bids`
	+ `spreadsheet2participants`
+ `pip_1`
	+ `config_pip_1`
	+ `master_pip_1`
	+ `00_fetch_data`
	+ `01_filt_eeg`
+ `ana_1`
	+ `config_ana_1`
	+ `master_ana_1`
	+ `00_fetch_data`


#### File prefixes
| File type            | Prefix | Function                                                                                         | [[Typing Standards]] |
| -------------------- | ------ | ------------------------------------------------------------------------------------------------ | -------------------- |
| Plotting             | plt_   | Plotting some part of the pipeline                                                               | snake_case           |
| Pipeline Data Script | 0x_    | Applies some data transformation tool. It is prefixed by a number to denote its application step | snake_case           |
| Test                 | test_  | A script for testing purposes not yet part of a pipeline.                                        | snake_case           |
| Loading Scripts      | load_  | A script whose purpose is to load raw data from an external source (e.g. .xlsx, .csv, .mat)      | snake_case           |
| Utils                | util_  | These are helper functions that can be generally be applied in scripts.                                                                                                 |                  snake_case    |
