<p align="center">
  <img src="https://quadvision.eu/bluesky_banner.png" />
</p>
<h1 align="center">
  BlueskyPoster
</h1>
<h3 align="center">
  Simple CLI tool for frequent posting, made in Rust
</h3>
<h2>How to use</h2>

<h3>Without compiling (Recommended)</h3>
- Head to the <a href="https://github.com/quadriVision/BlueskyPoster/releases">Releases</a> page<br>
- Download the latest executable (.exe for Windows, without file extension for Linux), alongside with "config.yaml" file<br>
- Download FFMpeg 7 or newer<br>
- Create an .env file with this text:<br>
BLUESKY_USERNAME_FULL=protofmantle.bluesky.social<br>
BLUESKY_PASSWOD=yourpassword123<br>
(these are just example values, replace those with your credentials)<br>
- Configure the application with the config.yaml file<br>
- Run the program<br>

<h3>With compiling (if you can't download a newer FFMpeg version)</h3>
- Download <a href="https://www.rust-lang.org/">Rust</a><br>
- Download the source code<br>
- Open cmd at the root folder<br>
- Type "cargo build --release"<br>
- Go to /target/release<br>
- Create an .env file with this text:<br>
BLUESKY_USERNAME_FULL=protofmantle.bluesky.social<br>
BLUESKY_PASSWOD=yourpassword123<br>
(these are just example values, replace those with your credentials)<br>
- Configure the application with the config.yaml file<br>
- Run the program<br>

<h2>Contact</h2>
<a href="mailto:quadvision@proton.me">E-mail</a><br>
<a href="https://quadvision.eu">Website</a><br>
<a href="https://x.com/ProtOfMantle">Twitter</a><br>
