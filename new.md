VERSION BUILD=8820413 RECORDER=FX

'open a new tab
TAB OPEN
TAB T=2

'goto online-editor, clear input and paste markdown from clipboard
URL GOTO=http://jrmoran.com/playground/markdown-live-editor/
TAG POS=1 TYPE=BUTTON ATTR=ID:clear
TAG POS=1 TYPE=TEXTAREA ATTR=ID:wmd-input CONTENT={{!CLIPBOARD}}