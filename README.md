# Vim Cheatsheet

The place where I gather some of the commands I regularly use with Vim while they aren't in my muscle memory.

# Vim editing shortcuts
r - replace one character at the cursor position
cw - change current word for a new word
R - begin replace mode
:e! - edit the current file always, discard any changes to current buffer
ds, cs - change surrounding characters

# Vim buffers shortcuts 
:ls - list buffers
:bn, :bp - switch buffers
:b # or :b name - go to specific buffer
:bd - delete the current buffer, will fail if unsaved
:bd! - delete the current buffer, will discard any changes


# Nerdtree shortcuts
o - open file/directory
go - open file but leave cursor in nerdtree
x - close the current node's parent
e - edit the current dir
p - jump to the current nodes parent
m - display the nerdtree menu (allows creating files and stuff)
q - close the Nerdtree window

# Ctrlp shortcuts
C-j , C-k - to navigate the result list
,b - restricts ctrlp.vim to open buffers

# Rails Shortcuts
:Emodel, :Eview, :Econtroller, are provided to :edit files by type, along with S, V, and T variants for :split, :vsplit, and :tabedit. Throw a bang on the end (:Emodel foo!) to automatically create the file with the standard boilerplate if it doesn't exist. :help rails-navigation
:A (alternate) and :R (related) for easy jumping between files
