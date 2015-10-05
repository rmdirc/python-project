# markov_python
Markov Chain text generator module

## How to add this to your project
1. Clone this repository into your Python project folder. Alternatively, you can download the zip archive and extract it into a directory in your project folder called `markov_python`.
2. Import this to your main project script by including the following at the top of the file `from markov_python.cc_markov import MarkovChain`


## How to use the Markov Chain text generator
1. After importing this module into your main project script, create an instance of MarkovChain and assign it to a variable. For example `mc = MarkovChain()`
2. Use one of the methods to read a local text file or a string. You can call this method multiple times to add additional data.
3. Call the `generate_text()` function to create text from the Markov Chain. You can call this method multiple times to generate additional data.


## License

This code is currently under the terms of the GPL v2 License which you can read about in the LICENSE file. This means it is free to use, copy, distribute, and modify, but you must disclose the original code and copyright under the same terms.
