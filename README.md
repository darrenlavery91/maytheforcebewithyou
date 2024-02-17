# MP3 Player with Visualizer (StarWars)

This project is a simple HTML-based MP3 player with a visualizer using the HTML5 Canvas element. It includes an interface to choose an MP3 file and visualize its frequency data in real-time.

![Screenshot](https://github.com/darrenlavery91/maytheforcebewithyou/raw/main/assets/148440040/023c6bc2-5ce1-4fff-94d8-3e2d525cfdb9.png)


## Requirements
- [Podman](https://podman.io/)

$ podman run quay.io/podman/hello

Trying to pull quay.io/podman/hello:latest...
Getting image source signatures
Copying blob a6b3126f3807 done
Copying config 25c667d086 done
Writing manifest to image destination
Storing signatures
Project:   https://github.com/containers/podman
Website:   https://podman.io
Documents: https://docs.podman.io
Twitter:   @Podman_io


## Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/darrenlavery91/maytheforcebewithyou.git
   cd maytheforcebewithyou
   ```

2. Build the Podman container:
   ```sh
   podman build -t mp3-player -f Dockerfile
   ```

3. Run the container:
   ```sh
   podman run -p 8080:80 mp3-player
   ```

4. Open your web browser and go to [http://localhost:8080/mp3_player.html](http://localhost:8080/mp3_player.html) to use the MP3 player with visualizer.

5. Use the "Choose files" button and select multiple mp3 files on your local machine, it will create a playlist in the ui, to skip songs just select the song name. Enjoy!

## Customization

- **Background Image:** Replace `1987321.jpg` with your preferred background image. Ensure the file is in the same directory as the Dockerfile.

- **Styling:** Modify the styling in the `<style>` section of `mp3_player.html` to suit your preferences.

## Note

- The provided Dockerfile assumes that the MP3 player HTML file (`mp3_player.html`) and the background image (`1987321.jpg`) are in the same directory as the Dockerfile.

- Make sure the paths in `mp3_player.html` are correct relative to the location where the Podman container runs.

- The project is set up to accept MP3 files for playback.

Feel free to customize the project and make it your own!
```
<img width="1278" alt="Screenshot 2024-02-17 at 10 57 44" src="https://github.com/darrenlavery91/maytheforcebewithyou/assets/148440040/023c6bc2-5ce1-4fff-94d8-3e2d525cfdb9">
