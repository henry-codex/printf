
<!DOCTYPE html>
<html>
  <head>
    
  </head>
  <body>
    <h1>0x11. C - printf Team Project</h1>
    <p>This is a group project for Holberton School students. The project involves writing a function in C that produces output according to a format.</p>
    <h2>Task</h2>
    <ol>
      <li>Write a function that produces output according to a format.</li>
      <li>Handle the following conversion specifiers: <code>%c</code>, <code>%s</code>, <code>%d</code>, <code>%i</code>, <code>%u</code>, <code>%o</code>, <code>%x</code>, <code>%X</code>.</li>
      <li>Use a local buffer of 1024 chars in order to call write as little as possible.</li>
      <li>Handle the following custom conversion specifier: <code>%r</code> - prints the reversed string.</li>
      <li>Handle the following flags for non-custom conversion specifiers:<ul>
          <li><code>+</code></li>
          <li><code> </code></li>
          <li><code>-</code></li>
          <li><code>#</code></li>
          <li><code>0</code></li>
        </ul></li>
      <li>Handle the following length modifiers for non-custom conversion specifiers:<ul>
          <li><code>l</code></li>
          <li><code>h</code></li>
        </ul></li>
      <li>Handle the field width for non-custom conversion specifiers.</li>
      <li>Handle the precision for non-custom conversion specifiers.</li>
      <li>Handle the following custom conversion specifier: <code>%R</code> - prints the rot13'ed string.</li>
      <li>Handle the following conversion specifier: <code>%p</code> - prints the pointer address.</li>
    </ol><p>Write a function that handles the following custom conversion specifier:</p>
<p><code>11. %R:</code>prints the rot13'ed string</p>
<p>Write a function that handles the following custom conversion specifier:</p>
<p><code>%t:</code>13.  prints a binary number (unsigned int) in a tree format</p>
<p>14. All the above options work well together.</p><h1>printf() function in C</h1>
    <p>This project involves implementing a simplified version of the printf() function in C programming language. This custom printf() function will be capable of printing various data types with specified formats to the standard output stream.</p>
    <h2>How to Use</h2>
    <p>The function <code>int _printf(const char *format, ...)</code> works in a similar manner to the standard printf() function. The first argument is a string that contains zero or more directives to specify the output format. The remaining arguments are the values to be formatted according to the directives.</p>
    <p>Here's an example of how to use the custom printf() function:</p>
    <pre><code>#include "main.h"
int main(void)
{
_printf("Hello, %s!\n", "world");
return (0);
}</code></pre>
<p>This code will output:</p>
<pre><code>Hello, world!</code></pre>
<h2>Custom Conversion Specifiers</h2>
<p>The custom conversion specifiers implemented in this project are:</p>
<ul>
<li><code>%b</code>: converts unsigned int to binary.</li>
<li><code>%u</code>: converts an unsigned int to an unsigned decimal notation.</li>
<li><code>%o</code>: converts an unsigned int to octal notation.</li>
<li><code>%x</code>: converts an unsigned int to hexadecimal (lowercase).</li>
<li><code>%X</code>: converts an unsigned int to hexadecimal (uppercase).</li>
<li><code>%S</code>: prints a string, replacing non-printable characters with their ASCII values in hexadecimal (uppercase).</li>
<li><code>%r</code>: prints a string in reverse.</li>
<li><code>%R</code>: prints a string in ROT13 encryption.</li>
</ul>
    
    <h2>Contributors</h2>
<ul>
  <li>Henry Tetteh (@henry-codex)</li>
  <li>Winifred Asmah (@winie-asmah)</li>
</ul>

<p>For more information, please refer to the <a href="https://github.com/henry-codex/printf">project repository</a>.</p>
  </body>
</html>




