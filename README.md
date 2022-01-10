<p align="center">
  <img src="/03 - ScreenShots/logo.png" alt="alt text" width="500" height="250">
</p>

# CTVB
 This Software is a compiler that transform valid C code into VB code.

# Objectifs :
The goal of this project is to build a translator from valid code written in C to another code that performs the same operation but in VB (Visual Basic).

# Structure :
The Translator contains three main files:
1. The Lexical ctvb.l analyzer.
2. The ctvb.y Syntax Analyzer.
3. The file to convert C_code.txt.

# The code :
* The code is in this [repo](https://github.com/MH-Chalhoub/CTVB) (Available upon request) .
* [Here](https://github.com/MH-Chalhoub/CTVB-Project/blob/main/02%20-%20Translator/ctvb.exe) you can find the GUI of the Translator.

# Algorithm :
The translator is used to convert a C code to VB by following the following path:
1. First it starts by reading the C code to convert a stream of characters into a stream of tokens according to predefined rules (Pattern) in the lexer (ctvb.l).
2. As follows, it will recognize this language using a set of rules (BNF) predefined in the parser (ctvb.y).
3. In the event of an error, the program prints the error message specifying the type (Lexical or Syntax) and the line and column of the occurrence of this error.
4. If the C code is valid it will be converted into the corresponding VB code. In addition a Log file (Log.txt) will be generated which describes the rules used to recognize the C code.


# Notes:
* CTVB abbreviation of C to VB translator.
* To run the code you will need GCC, Flex, Bison.
* If you want to know more about the project check out [Report](https://github.com/MH-Chalhoub/CTVB-Project/blob/main/01%20-%20Rapport/Rapport.docx)


# Screenshots :
### Project Proposal :
<p align="center">
<img src="/03 - ScreenShots/project_proposal_1.jpg" alt="alt text" width="450" height="400">
<img src="/03 - ScreenShots/project_proposal_2.jpg" alt="alt text" width="450" height="400">
</p>

### Tokens :
<p align="center">
<img src="/03 - ScreenShots/token_1.png" alt="alt text" width="902" height="400">
</p>

### Grammar :
<p align="center">
<img src="/03 - ScreenShots/grammar_2.png" alt="alt text" width="902"  height="400">
<img src="/03 - ScreenShots/grammar_3.png" alt="alt text" width="600" height="150">
<img src="/03 - ScreenShots/grammar_4.png" alt="alt text" width="300" height="150">
<img src="/03 - ScreenShots/grammar_5.png" alt="alt text" width="902"  height="700">
</p>

### Test :
<p align="center">
<img src="/03 - ScreenShots/result_4.PNG" alt="alt text" width="902"  height="500">
<img src="/03 - ScreenShots/result_1.PNG" alt="alt text" width="902"  height="500">
<img src="/03 - ScreenShots/result_2.PNG" alt="alt text" width="902"  height="500">
<img src="/03 - ScreenShots/result_3.PNG" alt="alt text" width="902"  height="500">
</p>
