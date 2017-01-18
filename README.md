# PI ProcessBook Tag Data Extractor

This tool can be used to extract extensive tag history from PI Server using ProcessBook only. The data can saved in CSV files (one file per tag).

The tool is implemented as VB script only (without any external libraries)

## Usage

* Open PDI in your ProcessBook
* Select tags you are willing to extract. Tags can be selected in one of the following ways:
 * Importing text file with a single tag name per line
 * Adding tag names manually
 * Retrieving tags from open displays of active ProcessBook file (*.PIW). To use this option make sure only 1 PIW file is open with at least a single Display is viewed.
* Select time period you are interested in
* Click Extract

You can change "Block size" value if you run low on memory, or PI Server is limited on how much data can be fetched per transaction (this value is an amount of tag samples extracted in a single iteration)
 
## Screenshots
![Screenshot](./Screenshot.png  "Screenshot")


## License

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.



-- Meir Tseitlin, Imubit