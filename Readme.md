# Json file to web
Front end created by https://github.com/flexdinesh/dev-landing-page

This project can convert your resume (Json format) to a fancy web page.   

1. Replace /src/info.json with your own information.   
2. Run ```&npm start```   
3. Open your browser localhost://3000  

Here is the example.

```json
{
    "name" : "Perry",
    "tags" : ["Java developer", "Looking for 2019 summer intern", "Can also fly above water"],
    "about" : ["I like backend and learn all the interesting tech.", "I stay close to the community", "My dream is to code crazily for days without any concern and anxious."],
    "github" : "https://github.com/PerrySong",
    "linkedin" : "www.linkedin.com/in/perrycrazycoding",
    "projects" : [
        {   
            "name" : "Crypto Portfolio",
            "desc" : "A Java-based web application with metadata fetched from the Last.fm APIs and processed using the multithreaded approach",
            "techs" : [
                "fab fa-js",
                "fab fa-react",
                "fab fa-node",
                "fab fa-aws"
            ],
            "links" : [
                    {
                        "name" : "Github",
                        "href" : "https://github.com/PerrySong/CryptoPortfolio-Nodejs"
                    }
                ]
        },
        {   
            "name" : "CandyFM",
            "desc" : "This is a Web app",
            "techs" : [
                "fab fa-java",
                "fab fa-html5",
                "fab fa-css3-alt",
                "fab fa-lastfm-square"
            ],
            "links" : [
                    {
                        "name" : "Github",
                        "href" : "https://github.com/PerrySong/CandyFm"
                    }
                ]
        },
        {   
            "name" : "AleperyChat",
            "desc" : "Online video chat Android app using Opentok and using Affectiva detect and evaluate users’ facial expression",
            "techs" : [
                "fab fa-java",
                "fab fa-android"
            ],
            "links" : [
                    {
                        "name" : "Github",
                        "href" : "https://github.com/PerrySong/AleperyChat"
                    }
                ]
        },
        {   
            "name" : "Real-Time News Web App",
            "desc" : "A real-time news scraping data pipeline which has news monitoring, scraping and deduping servic",
            "techs" : [
                "fab fa-python",
                "fab fa-node",
                "fab fa-html5",
                "fab fa-css3-alt"
            ],
            "links" : [
                    {
                        "name" : "Github",
                        "href" : "https://github.com/PerrySong/Top-crypto-news-api"
                    }
                ]
        },
        {   
            "name" : "RESTful Campground Web App",
            "desc" : "A social media web application for users to share campgrounds",
            "techs" : [
                "fab fa-js",
                "fab fa-node",
                "fab fa-html5",
                "fab fa-css3-alt"
            ],
            "links" : [
                    {
                        "name" : "Github",
                        "href" : "https://github.com/PerrySong/Top-crypto-news-api"
                    },
                    {
                        "name" : "Website",
                        "href" : "https://hidden-headland-22449.herokuapp.com/"
                    }
                ]
        }
    ]

}
```

## License

MIT © Dinesh Pandiyan