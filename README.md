<h1 align="center">title-meta</h1>
<p align="center">
    <i>title-meta is a database with the purpose of documenting the playability of Nintendo Switch™ titles on <a href="https://github.com/skyline-emu/skyline">Skyline emulator</a>.</i><br/><br>
</p>

### File structure
* Every title has its own directory, the name of which being its title id
* Inside a title's directory, there is a `meta.md` file and a `save` directory
* The `meta.md` file contains the name of the title, commit it was tested on, issues, notes, cheats, and links to saves
* The `save` folder contains zips of saves that are linked in `meta.md`

### Front-end
* The Skyline app will use our CDN to retrieve useful info from the respective `meta.md`s of a user's local titles
* Playability rating will show up clearly in-app, as well as other info (if you tap to see more details)
* Saves and cheats will be installable with one tap
* A website front-end for title-meta is also planned at some point in the future