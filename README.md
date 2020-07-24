# Jslexi
Small Javascript lexer implemented in a class.

The lexer is implemented in the function/class "Jslexy" included as part of the script in the index.html file, where there is a sample of use too.

This is very basic (however functional) lexer with some of 130 lines, aimed to be used as a base for a more specialized lexer instead of be used as it is.

The use is very simple:

'''
  lex = new Jslexy();
  lex.init('Hello\nWorld "Hi".');
  while (lex.next()) {
    console.log(lex.toktyp + '->' + lex.tok);
  }
'''
