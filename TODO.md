# TODO
- ~~Redo branches to use jump to memory instead of jump to offset~~
- ~~Macro to make `lit, xxx, branchz` more readable in asm code~~
- ~~Restructure dictionary to allow long word names~~
- Rewrite some forth words in aforth.S to assembly where the forth
  implementation is more complex
- ~~Figure out how a prompt can be provided in the outer interpreter~~
- Implement more control flow words
- ~~Facilitate hiding of words, and hide some internal words~~
- ~~Let primitive and forthword macros have better defaults for flags
  so usage does not need to specify in most cases~~
- Use system call to request more memory instead of defining max
  memory at build time
- Buffer stdin instead of one key at a time
- Introspect word definitions (like disassemble a forth word)
