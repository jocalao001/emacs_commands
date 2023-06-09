# Window management in Emacs

+ [ ] m to mark files
  + [ ] type x + yes (to delete te files selected)
+ [ ] u to unmark files
+ [ ] t to mark all the files on the directory
+ [ ] Mayus + u to unmark all files
+ [ ] %m select files to mark
  + [ ] type D to delete te files selected
+ [ ] Emacs Windows are split screens
+ [ ] C-x b (switch between buffers)
  + [ ] type out buffer and tab for auto-complete
  + [ ] hit enter to get a list of buffers in the folder
  + [ ] create practice buffer
+ [ ] C-x C-f (find-file)
+ [ ] C-x k (kill-buffer)
+ [ ] C-x C-s (save-buffer)
+ [ ] C-x 2 (split-window-vertically)
+ [ ] C-x 3 (split-window-horizontally)
+ [ ] C-x ^ (enlarge window)
+ [ ] C-x } (enlarge-window-horizontally)
+ [ ] C-x { (shrink-window-horizontally)
+ [ ] C-x - (shrink-window-if-larger-than-buffer)
+ [ ] C-x + (balance-windows)
+ [ ] (compare-windows)
+ [ ] C-x 4 f (find file in other window)
+ [ ] C-x 4 b (select buffer in other window)
+ [ ] C-M-v (scroll other buffer)
+ [ ] C-x o (move to other window)
+ [ ] C-x 0 (delete the window you are currently in)
+ [ ] C-x 1 (close all other windows)
+ [ ] (delete-windows-on) (delete all windows on a certain buffer)
+ [ ] C-x 5 2 (make-frame)
+ [ ] initial-frame-alist (controls size of the initial frame)
+ [ ] default-frame-alist (controls size of default frame)
+ [ ] C-x 5 o (move to other frame)
+ [ ] C-z (minimizes frame)
+ [ ] toggle-frame-fullscreen (maximizes current frame)
+ [ ] C-x s (save-some-buffers)
+ [ ] M-x rename-buffer
+ [ ] C-x C-w (save as)
+ [ ] C-x C-q (open buffer as read only - toggle between read only and write status if possible)
+ [ ] C-x 4 r (open file as read only in new window)
+ [ ] C-x 5 r (open file as read only in new frame)
+ [ ] C-x C-b (opens buffer list)
  + [ ] C-n, n, space (moves down)
  + [ ] C-p, p, backspace (moves up)
  + [ ] d or k marks buffer for deletion
  + [ ] u unmarks buffer
  + [ ] m marks the buffer
  + [ ] s saves buffer
  + [ ] x to execute delete or save command and other one letter commands
  + [ ] ~ mark buffer as unmodified
  + [ ] % toggle read only status of buffer (if possible)
  + [ ] 1 display buffer in fullscreen
  + [ ] 2 display buffer and next one in horizontal windows
  + [ ] f replace buffer list with this buffer
  + [ ] o replace other window with this buffer
  + [ ] v display buffers marked with m, Emacs creates all windows
  + [ ] q quit buffer list
+ [ ] from terminal - emacs file1 file2 file3
+ Editing Modes

Press enter after each of these commands

M-x refill-mode => this keeps paragraphs neat while editing.
M-x auto-fill-mode => auto-fill mode - formats paragraphs as you are writing them.
M-q fill-paragraph (try this out to show ...)
C-x u (undo)
M-x paragraph-indent-text-mode
C-p move up a line
C-f move down a line
C-f move forward a character
C-b move back a character
M-f move forward a word
M-b move back a word
C-u 10 C-f move forward 10 characters
C-u 15 C-b move back 15 characters
M-> move to the end of the file
M-< mvoe to the end of the file
M-g M-g go to line
C-e Move to the end of the line
M-e Move to the end of a sentence
C-a Move to the beginning of the line
M-a Move to the beginning of a sentence
M-} move to the end of a paragraph
M-{ move to the beginning of a paragraph
For page breaks:
C-x [ move back a page
C-x ] move forward a page
Make a page delimiter to break pages
Create a page break with C-q C-l
C-v (move down a screen)
M-v (move up a screen)
M-x goto-line enter
M-x goto-char enter
M-n repeat a command (n is the number of times you want to repeat) - hold down the alt key
I like C-u n command
C-l recenter

M-d => Kill-word (delete a word)
C-d => delete a character
C-k => kill line
M-C-k => delete from beginning of a line to the cursor.
"killing in Emacs puts deleted text into the kill ring"
C-y yank (get back what you've deleted)

Line 1.
Line 2.
Line 3.
Line 4.
C-u 4 C-p (move up 4 lines), then C-a C-u C-k (kill 4 lines), C-y (paste them back)

C-w (cut)
C-y (paste)

We can mark and cut.

This is the first line.
Line 2.
Line 3.
This is the last line. (now C-space or C-@ to set the mark), highlight all the items you want to cut, then C-w to cut, the C-y to repaste)

Kill a word backwards => M-Del, delete a whole chunk M-Shift-Backspace

C-x C-x => exchange point and mark

M-h => mark a paragraph and put cursor at the start of the paragraph. C-g to quit the mark.
C-x C-p => marks the current page

Copy text without deleting it (M-w)

M-y yank-pop (after C-y yanks previous yank)

C-w or M-w copies to clipboard

C-t transposes two letters miT

M-t transposes two words.
C-x C-t transposes two lines

Also:
M-x transpose-sentences enter
M-x transpose-paragraphs enter

M-c capitalize word when cursor is on the first letter tIm
M-u puts word in uppercase tim

M-l puts word in lowercase TIM

overwrite mode
M-x overwrite-mode enter
This is in overwrite mer

Revert buffer
M-x revert-buffer enter
M-x recover-file enter

CUA mode - you can turn this on from the menu
C-c copy
C-x cut
C-v paste

Display line numbers
M-x global-display-line-numbers-mode enter

Combinaciones de teclas más habituales

Moverse entre páginas

Ctrl v – Siguiente
Alt v – Anterior
Ctrl l – Limpia la pantalla y vuelve a mostrar todo el texto. Central el texto partiendo de la posición del cursor.

Moverse por el texto

Ctrl f – Mover el cursor un carácter hacia adelante (follow)
Ctrl b – Mover el cursor un cáracter hacia atrás (back)
Alt f – Mover el cursor una palabra hacia adelante (follow)
Alt b – Mover el cursor una palabra hacia atrás (back)
Ctrl n – Mover el curso a la siguiente línea en la misma posición (next)
Ctrl p – Mover el cursor a la línea anterior en la misma posición (previous)
Ctrl a – Mover el cursor al comienzo de la línea.
Ctrl e – Mover el cursor al final de la línea.
Alt a – Mover el cursor al inicio de una oración.
Alt e – Mover el cursor al final de una oración.

Modificar el texto

Ctrl k – Borra el texto (kill), pero lo mantiene guardado en caché, lo podemos recuperar con Ctrl y
Ctrl d – Borra un carácter (delete)
Ald d – Borra palabras enteras (delete)
Ctrl@ o Ctrl Espacio – Marca el texto seleccionado
Ctrl w – "Cortamos" el texto seleccionado.
Alt w – Copiamos el texto seleccionado.
Ctrl h – Marcamos todo el buffer, idéntico a un "Seleccionar todo"
Ctrl y – "Yanks text", pega el texto copiado o cortado con w
Alt y – Recorre "yanks" previos, podemos de esta manera recuperar algo que "matamos" varios Ctrl k antes.
Comandos
Ctrl g – Cancela comandos.
Ctrl x u – Deshacer.
Ctrl / – Deshacer.
Comandos con Ctrl x

Existen gran número de comandos que se inician con Ctrl x y después otra tecla.

Ctrl x Ctrl f – Abre un archivo que exista o sino lo crea. (file)
Ctrl x Ctrl s – Guardamos el archivo actual. (save)
Ctrl x s – Otra forma de guardar el archivo actual. (save)
Ctrl x Ctrl c – Sale de Emacs
Ctrl z – Suspende la sesión de Emacs. Podemos volver desde la consola de comandos con fg

Trabajar con el buffer

Ctrl x Ctrl b – Lista el buffer. En Emacs no existen "pestañas" o "ventanas**. Cada arhivo con el que trabajamos se guarda en el buffer. Podemos tener varios ficheros en el buffer, que podemos listar.
Ctrl x b – Cambiamos de fichero en el buffer. Podemos utilizar el tabulador para autocompletar el nombre.
Ctrl x k – Matar la sesión en el buffer.
Ctrl x s – Guardar la sesión actual en el buffer.

Otros comandos

Alt x – Modo comandos. Nos permite ejecutar comandos, como los ejemplo siguientes.
Alt x replace-string – Reemplazo de strings
Alta x recover file – Recupera el respaldo del archivo.
Ctrl s – Permite buscar strings en el texto hacia delante.
Ctrl r – Permite buscar strings en el texto hacia atrás.
Alt % – Para buscar y reemplazar.

Cambiar la vista

Ctrl x 2 – Divide la vista en 2 de forma horizontal.
Ctrl x 3 – Divide la vista en 2 de forma vertical.
Ctrl x 1 – Vuelve a dejar la vista a una.
Ctrl Alt v – Realiza scroll de la ventana donde no tenga foco.
Ctrl x o – Cambia el cursor de una vista a otra.
A medida que vaya trabajando con este editor, iré añadiendo nuevas combinaciones de teclas.
