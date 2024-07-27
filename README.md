# Radio Player Icecast/Shoutcast with API Now Playing and PWA Support

This project displays information about songs playing on Icecast/Shoutcast radio streams, including history, album art, lyrics, and Progressive Web App (PWA) support.

## Demo Screenshots

![Demo Screenshot](https://i.imgur.com/oULEMgZ.jpeg)

## Features:

* Displays current song, artist, and album art.
* History of played songs.
* Cover art of the current song
* Fetches song lyrics using Vagalume API ([Vagalume API](https://api.vagalume.com.br/docs/))
* Responsive design for mobile devices.
* Now available as a Progressive Web App (PWA) for enhanced user experience!
* Support for multiple radio stations

## Installation

1. Clone the repository or download the files.

2. Edit the <script> in the index.html

```javascript
<script>
            window.streams = {
                timeRefresh: 5000,
                stations: [
                    {
                        name: "Jailson Web Rádio",
                        hash: "jailson",
                        description: "Música sem parar",
                        logo: "assets/jailson_logo.png",
                        album:
                            "assets/jailson_cover.png",
                        cover:
                            "assets/jailson_cover.png",
                        api: "",
                        stream_url: "https://stream.zeno.fm/yn65fsaurfhvv",
                        tv_url: "https://eu1.servers10.com:2020/VideoPlayer/8106?autoplay=1",
                        server: "spotify",
                        program: {
                            time: "00:00",
                            name: "Jailson Web Radio",
                            description: "AO VIVO // ON AIR",
                        },
                        social: {
                            facebook: "https://facebook.com/",
                            twitter: "https://twitter.com/",
                            instagram: "https://www.instagram.com//",
                        },
                        apps: {
                            android: "#",
                            ios: "#",
                        },
                    },
                    {
                        name: "BENDICIÓN STEREO",
                        hash: "bendicion",
                        description: "Bendecidos para bendecir!",
                        logo: "assets/default.png",
                        album:
                            "assets/cover.png",
                        cover:
                            "assets/cover.png",
                        api: "get_stream_title.php?url=https://sv2.globalhostlive.com/proxy/bendistereo/stream2",
                        stream_url: "https://sv2.globalhostlive.com/proxy/bendistereo/stream2",
                        tv_url: "https://eu1.servers10.com:2020/VideoPlayer/8106?autoplay=1",
                        server: "spotify",
                        program: {
                            time: "11:00",
                            name: "Bendición Stereo",
                            description: "EN VIVO // ON AIR",
                        },
                        social: {
                            facebook: "https://facebook.com/BendicionStereo",
                            twitter: "https://twitter.com/BendiStereo",
                            instagram: "https://www.instagram.com/BendiStereo/",
                        },
                        apps: {
                            android: "#",
                            ios: "#",
                        },
                    },                    
                ],
            };
        </script>

 ```

3. Open The img folder and add your logo named "cover.png"


4. Just put the files in your server or use Free Hosting


## Free Hosting

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/jailsonsb2/RadioPlayer)
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/jailsonsb2/RadioPlayer)


## Contributing

1. Fork the project.
2. Create a branch for your feature (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

