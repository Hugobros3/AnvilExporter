# AnvilExporter
A tool for loading .mca region files and splitting them into Chunk Stories region files

It supports loading Minecraft Anvil ( works with 1.8.6 ) region files, parsing their NBT ( it doesn't parse properly all types of
primitives because I only needed the ByteArray tag to get the block ids, will fix later ) and then using the non-included
Chunk Stories format to export it. It might help you understand the workings of the Minecraft anvil region format, so here you go.

And YES it tolerates the weird case of NBT lists of TAG_END that other libraries don't. #steveaf
