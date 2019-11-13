###  The latest of mirror golang/x
##### Updated November 13, 2019
Here is the directory structure. You can use the `CTRL + F` shortcut to search for the files you need.

```
x
├── blog
│   ├── appengine.go
│   ├── app.yaml
│   ├── AUTHORS
│   ├── blog.go
│   ├── codereview.cfg
│   ├── content
│   │   ├── 10years
│   │   │   ├── gopher10th-large.jpg
│   │   │   ├── gopher10th-pin-large.jpg
│   │   │   ├── gopher10th-pin-small.jpg
│   │   │   ├── gopher10th-small.jpg
│   │   │   ├── img1.html
│   │   │   ├── img2.html
│   │   │   ├── pin1.html
│   │   │   └── pin2.html
│   │   ├── 10years.article
│   │   ├── 4years.article
│   │   ├── 4years-gopher.png
│   │   ├── 4years-graph.png
│   │   ├── 5years
│   │   │   ├── conferences.jpg
│   │   │   └── gophers5th.jpg
│   │   ├── 5years.article
│   │   ├── 6years.article
│   │   ├── 6years-gopher.png
│   │   ├── 7years.article
│   │   ├── 8years
│   │   │   ├── image1.png
│   │   │   ├── image2.png
│   │   │   ├── image3.png
│   │   │   ├── image4.png
│   │   │   └── photo.jpg
│   │   ├── 8years.article
│   │   ├── 9years.article
│   │   ├── 9years-graph.png
│   │   ├── 9years-iceland.jpg
│   │   ├── a-conversation-with-the-go-team.article
│   │   ├── advanced-go-concurrency-patterns.article
│   │   ├── appengine
│   │   │   └── main.go
│   │   ├── appengine-dec2013.article
│   │   ├── appengine-go111.article
│   │   ├── building-stathat-with-go.article
│   │   ├── building-stathat-with-go_stathat_architecture.png
│   │   ├── building-stathat-with-go_weather.png
│   │   ├── c-go-cgo.article
│   │   ├── community-outreach-working-group
│   │   │   └── project.png
│   │   ├── community-outreach-working-group.article
│   │   ├── company-questionnaire2018.article
│   │   ├── concurrency-is-not-parallelism.article
│   │   ├── conduct-2018.article
│   │   ├── constants
│   │   │   ├── bool.go
│   │   │   ├── complex1.go
│   │   │   ├── complex2.go
│   │   │   ├── complex3.go
│   │   │   ├── default1.go
│   │   │   ├── default2.go
│   │   │   ├── default3.go
│   │   │   ├── exercise1.go
│   │   │   ├── exercise2.go
│   │   │   ├── exercise3.go
│   │   │   ├── exercise4.go
│   │   │   ├── exercise5.go
│   │   │   ├── exercise6.go
│   │   │   ├── float1.go
│   │   │   ├── float2.go
│   │   │   ├── float3.go
│   │   │   ├── float4.go
│   │   │   ├── float5.go
│   │   │   ├── int1.go
│   │   │   ├── int2.go
│   │   │   ├── int3.go
│   │   │   ├── int4.go
│   │   │   ├── numbers1.go
│   │   │   ├── numbers2.go
│   │   │   ├── string1.go
│   │   │   ├── string2.go
│   │   │   ├── string3.go
│   │   │   ├── string4.go
│   │   │   └── syntax.go
│   │   ├── constants.article
│   │   ├── context
│   │   │   ├── google
│   │   │   │   └── google.go
│   │   │   ├── gorilla
│   │   │   │   └── gorilla.go
│   │   │   ├── interface.go
│   │   │   ├── server
│   │   │   │   └── server.go
│   │   │   ├── tomb
│   │   │   │   └── tomb.go
│   │   │   └── userip
│   │   │       └── userip.go
│   │   ├── context.article
│   │   ├── contributors-summit
│   │   │   ├── IMG_20170712_145844.jpg
│   │   │   ├── IMG_20170712_145854.jpg
│   │   │   ├── IMG_20170712_145905.jpg
│   │   │   ├── IMG_20170712_145911.jpg
│   │   │   └── IMG_20170712_145950.jpg
│   │   ├── contributors-summit-2019
│   │   │   └── group.jpg
│   │   ├── contributors-summit-2019.article
│   │   ├── contributors-summit.article
│   │   ├── contributor-workshop
│   │   │   ├── image10.png
│   │   │   ├── image11.png
│   │   │   ├── image12.png
│   │   │   ├── image13.png
│   │   │   ├── image14.jpg
│   │   │   ├── image15.png
│   │   │   ├── image16.png
│   │   │   ├── image17.png
│   │   │   ├── image18.jpg
│   │   │   ├── image19.png
│   │   │   ├── image1.png
│   │   │   ├── image20.jpg
│   │   │   ├── image21.jpg
│   │   │   ├── image22.png
│   │   │   ├── image23.png
│   │   │   ├── image2.jpg
│   │   │   ├── image3.png
│   │   │   ├── image4.jpg
│   │   │   ├── image5.jpg
│   │   │   ├── image6.png
│   │   │   ├── image7.png
│   │   │   ├── image8.jpg
│   │   │   └── image9.jpg
│   │   ├── contributor-workshop.article
│   │   ├── cover
│   │   │   ├── count.png
│   │   │   ├── pkg.cover
│   │   │   ├── pkg.go
│   │   │   ├── pkg_test.go
│   │   │   └── set.png
│   │   ├── cover.article
│   │   ├── debugging-go-code-status-report.article
│   │   ├── debugging-go-programs-with-gnu-debugger.article
│   │   ├── debugging-what-you-deploy.article
│   │   ├── debugging-what-you-deploy.graffle
│   │   ├── debugging-what-you-deploy.svg
│   │   ├── defer-panic-and-recover.article
│   │   ├── developer-experience.article
│   │   ├── docker.article
│   │   ├── docker-outyet.png
│   │   ├── error-handling-and-go.article
│   │   ├── errors-are-values.article
│   │   ├── examples
│   │   │   └── reverse.png
│   │   ├── examples.article
│   │   ├── experiment
│   │   │   ├── div-end.html
│   │   │   ├── div-indent.html
│   │   │   ├── div-quote.html
│   │   │   ├── expsimp1.graffle
│   │   │   ├── expsimp1.png
│   │   │   ├── expsimp2.graffle
│   │   │   ├── expsimp2.png
│   │   │   ├── yamldeps1.graffle
│   │   │   ├── yamldeps1.png
│   │   │   ├── yamldeps2.graffle
│   │   │   ├── yamldeps2.png
│   │   │   ├── yamldeps3.graffle
│   │   │   └── yamldeps3.png
│   │   ├── experiment.article
│   │   ├── first-class-functions-in-go-and-new-go.article
│   │   ├── first-go-program
│   │   │   └── slist.go
│   │   ├── first-go-program.article
│   │   ├── fosdem14.article
│   │   ├── from-zero-to-go-launching-on-google.article
│   │   ├── from-zero-to-go-launching-on-google_image00.png
│   │   ├── from-zero-to-go-launching-on-google_image01.jpg
│   │   ├── from-zero-to-go-launching-on-google_image02.png
│   │   ├── from-zero-to-go-launching-on-google_image03.png
│   │   ├── gccgo-in-gcc-471.article
│   │   ├── gcdk-whats-new-in-march-2019.article
│   │   ├── generate.article
│   │   ├── getthee-to-go-meetup.article
│   │   ├── getting-to-know-go-community.article
│   │   ├── gif-decoder-exercise-in-go-interfaces.article
│   │   ├── gif-decoder-exercise-in-go-interfaces_image00.jpg
│   │   ├── gif-decoder-exercise-in-go-interfaces_image01.gif
│   │   ├── gif-decoder-exercise-in-go-interfaces_image02.jpg
│   │   ├── gif-decoder-exercise-in-go-interfaces_image03.gif
│   │   ├── go1.10.article
│   │   ├── go1.11.article
│   │   ├── go1.12.article
│   │   ├── go1.13.article
│   │   ├── go1.13-errors.article
│   │   ├── go-11-is-released.article
│   │   ├── go-11-is-released_gopherbiplane5.jpg
│   │   ├── go12.article
│   │   ├── go1.3.article
│   │   ├── go1.4.article
│   │   ├── go1.5.article
│   │   ├── go15gc.article
│   │   ├── go1.6.article
│   │   ├── go1.7.article
│   │   ├── go1.7-binary-size.article
│   │   ├── go1.7-binary-size.png
│   │   ├── go1.8.article
│   │   ├── go1.9
│   │   │   └── helper_test.go
│   │   ├── go1.9.article
│   │   ├── go2draft.article
│   │   ├── go2-here-we-come.article
│   │   ├── go2-next-steps.article
│   │   ├── go-and-google-app-engine.article
│   │   ├── go-and-google-cloud-platform.article
│   │   ├── go-app-engine-sdk-155-released.article
│   │   ├── go-at-google-io-2011-videos.article
│   │   ├── go-at-google-io-2011-videos_gopher.jpg
│   │   ├── go-at-heroku.article
│   │   ├── go-at-io-frequently-asked-questions.article
│   │   ├── go-becomes-more-stable.article
│   │   ├── go-brand
│   │   │   ├── Go-BB_cover.jpg
│   │   │   ├── Go-BB_spread1.jpg
│   │   │   ├── Go-BB_spread2.jpg
│   │   │   ├── Go-brand-book-v1.0.pdf
│   │   │   ├── Go-Logo
│   │   │   │   ├── copyright.txt
│   │   │   │   ├── EPS
│   │   │   │   │   └── Go-Logo_Versions.eps
│   │   │   │   ├── Go-Logo_Versions.ai
│   │   │   │   ├── Go-Logo_Versions.pdf
│   │   │   │   ├── JPG
│   │   │   │   │   ├── Go-Logo_Aqua.jpg
│   │   │   │   │   ├── Go-Logo_Black.jpg
│   │   │   │   │   ├── Go-Logo_Blue.jpg
│   │   │   │   │   ├── Go-Logo_Fuchsia.jpg
│   │   │   │   │   ├── Go-Logo_LightBlue.jpg
│   │   │   │   │   └── Go-Logo_Yellow.jpg
│   │   │   │   ├── PNG
│   │   │   │   │   ├── Go-Logo_Aqua.png
│   │   │   │   │   ├── Go-Logo_Black.png
│   │   │   │   │   ├── Go-Logo_Blue.png
│   │   │   │   │   ├── Go-Logo_Fuchsia.png
│   │   │   │   │   ├── Go-Logo_LightBlue.png
│   │   │   │   │   ├── Go-Logo_White.png
│   │   │   │   │   └── Go-Logo_Yellow.png
│   │   │   │   └── SVG
│   │   │   │       ├── Go-Logo_Aqua.svg
│   │   │   │       ├── Go-Logo_Black.svg
│   │   │   │       ├── Go-Logo_Blue.svg
│   │   │   │       ├── Go-Logo_Fuchsia.svg
│   │   │   │       ├── Go-Logo_LightBlue.svg
│   │   │   │       ├── Go-Logo_White.svg
│   │   │   │       └── Go-Logo_Yellow.svg
│   │   │   ├── go-logos-1.0.zip
│   │   │   ├── go-slides-4up.jpg
│   │   │   ├── logos.jpg
│   │   │   └── video.html
│   │   ├── go-brand.article
│   │   ├── gobs-of-data.article
│   │   ├── go-cloud.article
│   │   ├── go-concurrency-patterns-timing-out-and.article
│   │   ├── go-developer-network.article
│   │   ├── godoc-documenting-go-code.article
│   │   ├── go-fmt-your-code.article
│   │   ├── go-fonts
│   │   │   ├── abdgpq-mono.png
│   │   │   ├── abdgpq-proportional.png
│   │   │   ├── go-font-code.png
│   │   │   ├── go-font-greek.png
│   │   │   ├── go-font-jabberwocky.png
│   │   │   ├── go-mono.png
│   │   │   └── go-regular.png
│   │   ├── go-fonts.article
│   │   ├── go-for-app-engine-is-now-generally.article
│   │   ├── go-imagedraw-package_20.png
│   │   ├── go-imagedraw-package_2a.png
│   │   ├── go-imagedraw-package_2b.png
│   │   ├── go-imagedraw-package_2c.png
│   │   ├── go-imagedraw-package_2d.png
│   │   ├── go-imagedraw-package_2e.png
│   │   ├── go-imagedraw-package_2f.png
│   │   ├── go-imagedraw-package.article
│   │   ├── go-image-package.article
│   │   ├── go-image-package_image-package-01.png
│   │   ├── go-image-package_image-package-02.png
│   │   ├── go-image-package_image-package-03.png
│   │   ├── go-image-package_image-package-04.png
│   │   ├── go-image-package_image-package-05.png
│   │   ├── go-maps-in-action
│   │   │   ├── list.go
│   │   │   └── people.go
│   │   ├── go-maps-in-action.article
│   │   ├── go-one-year-ago-today.article
│   │   ├── gopher
│   │   │   ├── avatars.png
│   │   │   ├── glenda.png
│   │   │   ├── gopher.png
│   │   │   ├── header.jpg
│   │   │   ├── logo.png
│   │   │   ├── plush.jpg
│   │   │   ├── portrait.jpg
│   │   │   ├── prototype.jpg
│   │   │   ├── usergroups.png
│   │   │   ├── vinyl.jpg
│   │   │   └── wfmu.jpg
│   │   ├── gopher.article
│   │   ├── gopherbelly300.jpg
│   │   ├── gopherbelly.html
│   │   ├── gopherchina
│   │   │   ├── image00.jpg
│   │   │   ├── image01.jpg
│   │   │   ├── image02.jpg
│   │   │   ├── image03.jpg
│   │   │   ├── image04.jpg
│   │   │   ├── image05.jpg
│   │   │   └── image06.jpg
│   │   ├── gopherchina.article
│   │   ├── gophercon
│   │   │   ├── image00.jpg
│   │   │   ├── image01.jpg
│   │   │   └── image02.jpg
│   │   ├── gophercon2015.article
│   │   ├── gophercon2015.caption
│   │   ├── gophercon2015.jpg
│   │   ├── gophercon.article
│   │   ├── gophergala
│   │   │   └── fancygopher.jpg
│   │   ├── gophergala.article
│   │   ├── go-programming-language-turns-two.article
│   │   ├── go-programming-language-turns-two_costume.jpg
│   │   ├── go-programming-language-turns-two_gophers.jpg
│   │   ├── go-programming-session-video-from.article
│   │   ├── gos-declaration-syntax.article
│   │   ├── go-slices-usage-and-internals.article
│   │   ├── go-slices-usage-and-internals_slice-1.png
│   │   ├── go-slices-usage-and-internals_slice-2.png
│   │   ├── go-slices-usage-and-internals_slice-3.png
│   │   ├── go-slices-usage-and-internals_slice-array.png
│   │   ├── go-slices-usage-and-internals_slice-struct.png
│   │   ├── gothamgo
│   │   │   └── gothamgo.jpg
│   │   ├── gothamgo.article
│   │   ├── go-turns-three.article
│   │   ├── gouk15
│   │   │   └── gouk.jpg
│   │   ├── gouk15.article
│   │   ├── go-updates-in-app-engine-171.article
│   │   ├── go-version-1-is-released.article
│   │   ├── go-version-1-is-released_gophermega.jpg
│   │   ├── go-videos-from-google-io-2012.article
│   │   ├── go-whats-new-in-march-2010.article
│   │   ├── go-wins-2010-bossie-award.article
│   │   ├── h2push
│   │   │   ├── networktimeline.png
│   │   │   ├── pusher.go
│   │   │   ├── server
│   │   │   │   ├── cert.pem
│   │   │   │   ├── key.pem
│   │   │   │   ├── main.go
│   │   │   │   └── static
│   │   │   │       ├── app.js
│   │   │   │       └── style.css
│   │   │   └── serverpush.svg
│   │   ├── h2push.article
│   │   ├── hello-china.article
│   │   ├── http-tracing
│   │   │   ├── client.go
│   │   │   └── trace.go
│   │   ├── http-tracing.article
│   │   ├── introducing-gofix.article
│   │   ├── introducing-go-playground.article
│   │   ├── introducing-go-playground_Untitled.png
│   │   ├── io2014
│   │   │   ├── booth.jpg
│   │   │   ├── collage.jpg
│   │   │   ├── crowd.jpg
│   │   │   └── summerfest.jpg
│   │   ├── io2014.article
│   │   ├── ismmkeynote
│   │   │   ├── image10.png
│   │   │   ├── image11.png
│   │   │   ├── image12.png
│   │   │   ├── image13.png
│   │   │   ├── image14.png
│   │   │   ├── image15.png
│   │   │   ├── image16.png
│   │   │   ├── image17.png
│   │   │   ├── image18.png
│   │   │   ├── image19.png
│   │   │   ├── image1.png
│   │   │   ├── image20.png
│   │   │   ├── image21.png
│   │   │   ├── image22.png
│   │   │   ├── image23.png
│   │   │   ├── image24.png
│   │   │   ├── image25.png
│   │   │   ├── image26.png
│   │   │   ├── image27.png
│   │   │   ├── image28.png
│   │   │   ├── image29.png
│   │   │   ├── image2.png
│   │   │   ├── image30.png
│   │   │   ├── image31.png
│   │   │   ├── image32.png
│   │   │   ├── image33.png
│   │   │   ├── image34.png
│   │   │   ├── image35.png
│   │   │   ├── image36.png
│   │   │   ├── image37.png
│   │   │   ├── image38.png
│   │   │   ├── image39.png
│   │   │   ├── image3.png
│   │   │   ├── image40.png
│   │   │   ├── image41.png
│   │   │   ├── image42.png
│   │   │   ├── image43.png
│   │   │   ├── image44.png
│   │   │   ├── image45.png
│   │   │   ├── image46.png
│   │   │   ├── image47.png
│   │   │   ├── image48.png
│   │   │   ├── image49.png
│   │   │   ├── image4.png
│   │   │   ├── image50.png
│   │   │   ├── image51.png
│   │   │   ├── image52.png
│   │   │   ├── image53.png
│   │   │   ├── image54.png
│   │   │   ├── image55.png
│   │   │   ├── image56.png
│   │   │   ├── image57.png
│   │   │   ├── image58.png
│   │   │   ├── image59.png
│   │   │   ├── image5.png
│   │   │   ├── image60.png
│   │   │   ├── image61.png
│   │   │   ├── image62.png
│   │   │   ├── image63.png
│   │   │   ├── image64.png
│   │   │   ├── image65.png
│   │   │   ├── image66.png
│   │   │   ├── image67.png
│   │   │   ├── image68.png
│   │   │   ├── image69.png
│   │   │   ├── image6.png
│   │   │   ├── image7.png
│   │   │   ├── image8.png
│   │   │   └── image9.png
│   │   ├── ismmkeynote.article
│   │   ├── json-and-go.article
│   │   ├── json-rpc-tale-of-interfaces.article
│   │   ├── laws-of-reflection.article
│   │   ├── learn-go-from-your-browser.article
│   │   ├── matchlang
│   │   │   ├── complete.go
│   │   │   ├── display.go
│   │   │   └── tags.html
│   │   ├── matchlang.article
│   │   ├── migrating-to-go-modules.article
│   │   ├── module-mirror-launch
│   │   │   ├── proxy-protocol.png
│   │   │   ├── sumdb-protocol.png
│   │   │   └── tree.png
│   │   ├── module-mirror-launch.article
│   │   ├── modules2019
│   │   │   ├── code.graffle
│   │   │   └── code.png
│   │   ├── modules2019.article
│   │   ├── new-talk-and-tutorials.article
│   │   ├── normalization
│   │   │   ├── table1.html
│   │   │   └── table2.html
│   │   ├── normalization.article
│   │   ├── open-source.article
│   │   ├── organizing-go-code.article
│   │   ├── oscon.article
│   │   ├── osconreport
│   │   │   ├── meetup.png
│   │   │   ├── random.png
│   │   │   ├── talks.png
│   │   │   └── workshops.png
│   │   ├── osconreport.article
│   │   ├── package-names.article
│   │   ├── pipelines
│   │   │   ├── bounded.go
│   │   │   ├── parallel.go
│   │   │   ├── serial.go
│   │   │   ├── sqbuffer.go
│   │   │   ├── sqdone1.go
│   │   │   ├── sqdone2.go
│   │   │   ├── sqdone3.go
│   │   │   ├── sqfan.go
│   │   │   ├── sqleak.go
│   │   │   ├── square2.go
│   │   │   └── square.go
│   │   ├── pipelines.article
│   │   ├── playground
│   │   │   ├── net.go
│   │   │   ├── os.go
│   │   │   ├── overview.png
│   │   │   └── time.go
│   │   ├── playground.article
│   │   ├── preview-of-go-version-1.article
│   │   ├── profiling-go-programs.article
│   │   ├── profiling-go-programs_havlak1a-75.png
│   │   ├── profiling-go-programs_havlak1-hash_lookup-75.png
│   │   ├── profiling-go-programs_havlak4a-mallocgc.png
│   │   ├── profiling-go-programs_havlak4a-mallocgc-trim.png
│   │   ├── publishing-go-modules.article
│   │   ├── qihoo
│   │   │   ├── image00.png
│   │   │   ├── image01.png
│   │   │   ├── image02.png
│   │   │   ├── image03.png
│   │   │   └── table.png
│   │   ├── qihoo.article
│   │   ├── race-detector
│   │   │   ├── blackhole.go
│   │   │   ├── timer-fixed.go
│   │   │   └── timer.go
│   │   ├── race-detector.article
│   │   ├── real-go-projects-smarttwitter-and-webgo.article
│   │   ├── share-memory-by-communicating.article
│   │   ├── slices
│   │   │   ├── prog010.go
│   │   │   ├── prog020.go
│   │   │   ├── prog030.go
│   │   │   ├── prog040.go
│   │   │   ├── prog050.go
│   │   │   ├── prog060.go
│   │   │   ├── prog070.go
│   │   │   ├── prog080.go
│   │   │   ├── prog090.go
│   │   │   ├── prog100.go
│   │   │   ├── prog110.go
│   │   │   ├── prog120.go
│   │   │   ├── prog130.go
│   │   │   ├── prog140.go
│   │   │   └── prog150.go
│   │   ├── slices.article
│   │   ├── spotlight-on-external-go-libraries.article
│   │   ├── store
│   │   │   └── gophers.jpg
│   │   ├── store.article
│   │   ├── strings
│   │   │   ├── basic.go
│   │   │   ├── encoding.go
│   │   │   ├── range.go
│   │   │   └── utf8.go
│   │   ├── strings.article
│   │   ├── subtests.article
│   │   ├── survey2016
│   │   │   ├── aboutme.svg
│   │   │   ├── adequate.svg
│   │   │   ├── agree6.svg
│   │   │   ├── answers.svg
│   │   │   ├── areas.svg
│   │   │   ├── attend.svg
│   │   │   ├── background.html
│   │   │   ├── challenge2.svg
│   │   │   ├── challenge.svg
│   │   │   ├── community.html
│   │   │   ├── contribute1.svg
│   │   │   ├── contribute2.svg
│   │   │   ├── country.svg
│   │   │   ├── deploy.svg
│   │   │   ├── dev.html
│   │   │   ├── docs.svg
│   │   │   ├── ed-feature.svg
│   │   │   ├── ed-satisfy.svg
│   │   │   ├── ed.svg
│   │   │   ├── effective.html
│   │   │   ├── effective.svg
│   │   │   ├── final.svg
│   │   │   ├── howlong.svg
│   │   │   ├── identify.svg
│   │   │   ├── improve.svg
│   │   │   ├── keyword.svg
│   │   │   ├── lang-expertise.svg
│   │   │   ├── lang-preference.svg
│   │   │   ├── library.svg
│   │   │   ├── like.svg
│   │   │   ├── mkhtml.go
│   │   │   ├── news.svg
│   │   │   ├── project.html
│   │   │   ├── quotes.html
│   │   │   ├── README
│   │   │   ├── recommend.svg
│   │   │   ├── system.svg
│   │   │   ├── usage.html
│   │   │   ├── uses.svg
│   │   │   ├── welcome.svg
│   │   │   ├── welcoming.svg
│   │   │   ├── when.svg
│   │   │   ├── why-not.svg
│   │   │   └── why-not-text.svg
│   │   ├── survey2016.article
│   │   ├── survey2016-results.article
│   │   ├── survey2017
│   │   │   ├── about-me-comp.svg
│   │   │   ├── about-me.svg
│   │   │   ├── access.svg
│   │   │   ├── agree-community.svg
│   │   │   ├── agree-diagnose.svg
│   │   │   ├── agree-practices.svg
│   │   │   ├── agree-project.svg
│   │   │   ├── agree-work-well.svg
│   │   │   ├── answers.svg
│   │   │   ├── area-comp.svg
│   │   │   ├── area.svg
│   │   │   ├── background.html
│   │   │   ├── challenge.svg
│   │   │   ├── community.html
│   │   │   ├── community.svg
│   │   │   ├── contrib.svg
│   │   │   ├── country.svg
│   │   │   ├── deploy-go-comp.svg
│   │   │   ├── deploy-go.svg
│   │   │   ├── deploy-nongo-comp.svg
│   │   │   ├── deploy-nongo.svg
│   │   │   ├── dev.html
│   │   │   ├── editor-comp.svg
│   │   │   ├── editor.svg
│   │   │   ├── effective.html
│   │   │   ├── event.svg
│   │   │   ├── final.svg
│   │   │   ├── freq.svg
│   │   │   ├── how-long.svg
│   │   │   ├── identify.svg
│   │   │   ├── implemented.svg
│   │   │   ├── keyword.svg
│   │   │   ├── lang-exp.svg
│   │   │   ├── lang-pref.svg
│   │   │   ├── last-year.svg
│   │   │   ├── libraries.svg
│   │   │   ├── mkhtml.go
│   │   │   ├── news.svg
│   │   │   ├── open-source.svg
│   │   │   ├── os.svg
│   │   │   ├── project.html
│   │   │   ├── sat-editor.svg
│   │   │   ├── usage.html
│   │   │   ├── uses-comp.svg
│   │   │   ├── uses.svg
│   │   │   ├── why-not-comp.svg
│   │   │   └── why-not.svg
│   │   ├── survey2017.article
│   │   ├── survey2017-results.article
│   │   ├── survey2018
│   │   │   ├── fig10.svg
│   │   │   ├── fig11.svg
│   │   │   ├── fig12.svg
│   │   │   ├── fig13.svg
│   │   │   ├── fig14.svg
│   │   │   ├── fig15.svg
│   │   │   ├── fig16.svg
│   │   │   ├── fig17.svg
│   │   │   ├── fig18.svg
│   │   │   ├── fig19.svg
│   │   │   ├── fig1.svg
│   │   │   ├── fig20.svg
│   │   │   ├── fig21.svg
│   │   │   ├── fig22.svg
│   │   │   ├── fig23.svg
│   │   │   ├── fig24.svg
│   │   │   ├── fig25.svg
│   │   │   ├── fig26.svg
│   │   │   ├── fig27.svg
│   │   │   ├── fig28.svg
│   │   │   ├── fig29.svg
│   │   │   ├── fig2.svg
│   │   │   ├── fig3.svg
│   │   │   ├── fig4.svg
│   │   │   ├── fig5.svg
│   │   │   ├── fig6.svg
│   │   │   ├── fig7.svg
│   │   │   ├── fig8.svg
│   │   │   ├── fig9.svg
│   │   │   ├── reading.html
│   │   │   └── style.html
│   │   ├── survey2018.article
│   │   ├── survey2018-results.article
│   │   ├── the-app-engine-sdk-and-workspaces-gopath.article
│   │   ├── the-path-to-go-1.article
│   │   ├── third-party-libraries-goprotobuf-and.article
│   │   ├── toward-go2
│   │   │   ├── div-end.html
│   │   │   ├── div-indent.html
│   │   │   ├── error.png
│   │   │   ├── go1-preview.png
│   │   │   ├── go1-release.png
│   │   │   ├── mail.png
│   │   │   ├── process2.graffle
│   │   │   ├── process2.png
│   │   │   ├── process2.svg
│   │   │   ├── process34.graffle
│   │   │   ├── process34.png
│   │   │   ├── process34.svg
│   │   │   ├── process5.graffle
│   │   │   ├── process5.png
│   │   │   ├── process5.svg
│   │   │   ├── process.graffle
│   │   │   ├── process.png
│   │   │   ├── process.svg
│   │   │   └── tweet.png
│   │   ├── toward-go2.article
│   │   ├── two-go-talks-lexical-scanning-in-go-and.article
│   │   ├── two-recent-go-articles.article
│   │   ├── two-recent-go-talks.article
│   │   ├── upcoming-google-io-go-events.article
│   │   ├── using-go-modules.article
│   │   ├── v2-go-modules.article
│   │   ├── versioning-proposal.article
│   │   ├── why-generics.article
│   │   ├── wire.article
│   │   └── writing-scalable-app-engine.article
│   ├── CONTRIBUTING.md
│   ├── CONTRIBUTORS
│   ├── go.mod
│   ├── go.sum
│   ├── LICENSE
│   ├── local.go
│   ├── local_test.go
│   ├── PATENTS
│   ├── README.md
│   ├── rewrite.go
│   ├── static
│   │   ├── favicon.ico
│   │   ├── fonts
│   │   │   ├── Go-BoldItalic.woff
│   │   │   ├── Go-Bold.woff
│   │   │   ├── Go-Italic.woff
│   │   │   ├── GoMedium-Italic.woff
│   │   │   ├── GoMedium.woff
│   │   │   ├── GoMono-BoldItalic.woff
│   │   │   ├── GoMono-Bold.woff
│   │   │   ├── GoMono-Italic.woff
│   │   │   ├── GoMono.woff
│   │   │   └── GoRegular.woff
│   │   └── fonts.css
│   ├── support
│   │   └── racy
│   │       └── racy.go
│   └── template
│       ├── article.tmpl
│       ├── doc.tmpl
│       ├── home.tmpl
│       ├── index.tmpl
│       └── root.tmpl
├── crypto
│   ├── acme
│   │   ├── acme.go
│   │   ├── acme_test.go
│   │   ├── autocert
│   │   │   ├── autocert.go
│   │   │   ├── autocert_test.go
│   │   │   ├── cache.go
│   │   │   ├── cache_test.go
│   │   │   ├── example_test.go
│   │   │   ├── internal
│   │   │   │   └── acmetest
│   │   │   │       └── ca.go
│   │   │   ├── listener.go
│   │   │   ├── renewal.go
│   │   │   └── renewal_test.go
│   │   ├── http.go
│   │   ├── http_test.go
│   │   ├── internal
│   │   │   └── acmeprobe
│   │   │       └── prober.go
│   │   ├── jws.go
│   │   ├── jws_test.go
│   │   ├── rfc8555.go
│   │   ├── rfc8555_test.go
│   │   ├── types.go
│   │   ├── types_test.go
│   │   └── version_go112.go
│   ├── argon2
│   │   ├── argon2.go
│   │   ├── argon2_test.go
│   │   ├── blake2b.go
│   │   ├── blamka_amd64.go
│   │   ├── blamka_amd64.s
│   │   ├── blamka_generic.go
│   │   └── blamka_ref.go
│   ├── AUTHORS
│   ├── bcrypt
│   │   ├── base64.go
│   │   ├── bcrypt.go
│   │   └── bcrypt_test.go
│   ├── blake2b
│   │   ├── blake2b_amd64.go
│   │   ├── blake2b_amd64.s
│   │   ├── blake2bAVX2_amd64.go
│   │   ├── blake2bAVX2_amd64.s
│   │   ├── blake2b_generic.go
│   │   ├── blake2b.go
│   │   ├── blake2b_ref.go
│   │   ├── blake2b_test.go
│   │   ├── blake2x.go
│   │   └── register.go
│   ├── blake2s
│   │   ├── blake2s_386.go
│   │   ├── blake2s_386.s
│   │   ├── blake2s_amd64.go
│   │   ├── blake2s_amd64.s
│   │   ├── blake2s_generic.go
│   │   ├── blake2s.go
│   │   ├── blake2s_ref.go
│   │   ├── blake2s_test.go
│   │   ├── blake2x.go
│   │   └── register.go
│   ├── blowfish
│   │   ├── block.go
│   │   ├── blowfish_test.go
│   │   ├── cipher.go
│   │   └── const.go
│   ├── bn256
│   │   ├── bn256.go
│   │   ├── bn256_test.go
│   │   ├── constants.go
│   │   ├── curve.go
│   │   ├── example_test.go
│   │   ├── gfp12.go
│   │   ├── gfp2.go
│   │   ├── gfp6.go
│   │   ├── optate.go
│   │   └── twist.go
│   ├── cast5
│   │   ├── cast5.go
│   │   └── cast5_test.go
│   ├── chacha20
│   │   ├── chacha_arm64.go
│   │   ├── chacha_arm64.s
│   │   ├── chacha_generic.go
│   │   ├── chacha_noasm.go
│   │   ├── chacha_ppc64le.go
│   │   ├── chacha_ppc64le.s
│   │   ├── chacha_s390x.go
│   │   ├── chacha_s390x.s
│   │   ├── chacha_test.go
│   │   ├── vectors_test.go
│   │   └── xor.go
│   ├── chacha20poly1305
│   │   ├── chacha20poly1305_amd64.go
│   │   ├── chacha20poly1305_amd64.s
│   │   ├── chacha20poly1305_generic.go
│   │   ├── chacha20poly1305.go
│   │   ├── chacha20poly1305_noasm.go
│   │   ├── chacha20poly1305_test.go
│   │   ├── chacha20poly1305_vectors_test.go
│   │   └── xchacha20poly1305.go
│   ├── codereview.cfg
│   ├── CONTRIBUTING.md
│   ├── CONTRIBUTORS
│   ├── cryptobyte
│   │   ├── asn1
│   │   │   └── asn1.go
│   │   ├── asn1.go
│   │   ├── asn1_test.go
│   │   ├── builder.go
│   │   ├── cryptobyte_test.go
│   │   ├── example_test.go
│   │   └── string.go
│   ├── curve25519
│   │   ├── curve25519_amd64.go
│   │   ├── curve25519_amd64.s
│   │   ├── curve25519_generic.go
│   │   ├── curve25519.go
│   │   ├── curve25519_noasm.go
│   │   ├── curve25519_test.go
│   │   └── vectors_test.go
│   ├── ed25519
│   │   ├── ed25519.go
│   │   ├── ed25519_go113.go
│   │   ├── ed25519_test.go
│   │   ├── go113_test.go
│   │   ├── internal
│   │   │   └── edwards25519
│   │   │       ├── const.go
│   │   │       └── edwards25519.go
│   │   └── testdata
│   │       └── sign.input.gz
│   ├── go.mod
│   ├── go.sum
│   ├── hkdf
│   │   ├── example_test.go
│   │   ├── hkdf.go
│   │   └── hkdf_test.go
│   ├── internal
│   │   └── subtle
│   │       ├── aliasing_appengine.go
│   │       ├── aliasing.go
│   │       └── aliasing_test.go
│   ├── LICENSE
│   ├── md4
│   │   ├── example_test.go
│   │   ├── md4block.go
│   │   ├── md4.go
│   │   └── md4_test.go
│   ├── nacl
│   │   ├── auth
│   │   │   ├── auth.go
│   │   │   ├── auth_test.go
│   │   │   └── example_test.go
│   │   ├── box
│   │   │   ├── box.go
│   │   │   ├── box_test.go
│   │   │   └── example_test.go
│   │   ├── secretbox
│   │   │   ├── example_test.go
│   │   │   ├── secretbox.go
│   │   │   └── secretbox_test.go
│   │   └── sign
│   │       ├── sign.go
│   │       └── sign_test.go
│   ├── ocsp
│   │   ├── ocsp.go
│   │   └── ocsp_test.go
│   ├── openpgp
│   │   ├── armor
│   │   │   ├── armor.go
│   │   │   ├── armor_test.go
│   │   │   └── encode.go
│   │   ├── canonical_text.go
│   │   ├── canonical_text_test.go
│   │   ├── clearsign
│   │   │   ├── clearsign.go
│   │   │   └── clearsign_test.go
│   │   ├── elgamal
│   │   │   ├── elgamal.go
│   │   │   └── elgamal_test.go
│   │   ├── errors
│   │   │   └── errors.go
│   │   ├── keys_data_test.go
│   │   ├── keys.go
│   │   ├── keys_test.go
│   │   ├── packet
│   │   │   ├── compressed.go
│   │   │   ├── compressed_test.go
│   │   │   ├── config.go
│   │   │   ├── encrypted_key.go
│   │   │   ├── encrypted_key_test.go
│   │   │   ├── literal.go
│   │   │   ├── ocfb.go
│   │   │   ├── ocfb_test.go
│   │   │   ├── one_pass_signature.go
│   │   │   ├── opaque.go
│   │   │   ├── opaque_test.go
│   │   │   ├── packet.go
│   │   │   ├── packet_test.go
│   │   │   ├── private_key.go
│   │   │   ├── private_key_test.go
│   │   │   ├── public_key.go
│   │   │   ├── public_key_test.go
│   │   │   ├── public_key_v3.go
│   │   │   ├── public_key_v3_test.go
│   │   │   ├── reader.go
│   │   │   ├── signature.go
│   │   │   ├── signature_test.go
│   │   │   ├── signature_v3.go
│   │   │   ├── signature_v3_test.go
│   │   │   ├── symmetrically_encrypted.go
│   │   │   ├── symmetrically_encrypted_test.go
│   │   │   ├── symmetric_key_encrypted.go
│   │   │   ├── symmetric_key_encrypted_test.go
│   │   │   ├── userattribute.go
│   │   │   ├── userattribute_test.go
│   │   │   ├── userid.go
│   │   │   └── userid_test.go
│   │   ├── read.go
│   │   ├── read_test.go
│   │   ├── s2k
│   │   │   ├── s2k.go
│   │   │   └── s2k_test.go
│   │   ├── write.go
│   │   └── write_test.go
│   ├── otr
│   │   ├── libotr_test_helper.c
│   │   ├── otr.go
│   │   ├── otr_test.go
│   │   └── smp.go
│   ├── PATENTS
│   ├── pbkdf2
│   │   ├── pbkdf2.go
│   │   └── pbkdf2_test.go
│   ├── pkcs12
│   │   ├── bmp-string.go
│   │   ├── bmp-string_test.go
│   │   ├── crypto.go
│   │   ├── crypto_test.go
│   │   ├── errors.go
│   │   ├── internal
│   │   │   └── rc2
│   │   │       ├── bench_test.go
│   │   │       ├── rc2.go
│   │   │       └── rc2_test.go
│   │   ├── mac.go
│   │   ├── mac_test.go
│   │   ├── pbkdf.go
│   │   ├── pbkdf_test.go
│   │   ├── pkcs12.go
│   │   ├── pkcs12_test.go
│   │   └── safebags.go
│   ├── poly1305
│   │   ├── bits_compat.go
│   │   ├── bits_go1.13.go
│   │   ├── mac_noasm.go
│   │   ├── poly1305.go
│   │   ├── poly1305_test.go
│   │   ├── sum_amd64.go
│   │   ├── sum_amd64.s
│   │   ├── sum_arm.go
│   │   ├── sum_arm.s
│   │   ├── sum_generic.go
│   │   ├── sum_noasm.go
│   │   ├── sum_ppc64le.go
│   │   ├── sum_ppc64le.s
│   │   ├── sum_s390x.go
│   │   ├── sum_s390x.s
│   │   ├── sum_vmsl_s390x.s
│   │   └── vectors_test.go
│   ├── README.md
│   ├── ripemd160
│   │   ├── ripemd160block.go
│   │   ├── ripemd160.go
│   │   └── ripemd160_test.go
│   ├── salsa20
│   │   ├── salsa
│   │   │   ├── hsalsa20.go
│   │   │   ├── salsa208.go
│   │   │   ├── salsa20_amd64.go
│   │   │   ├── salsa20_amd64.s
│   │   │   ├── salsa20_amd64_test.go
│   │   │   ├── salsa20_noasm.go
│   │   │   ├── salsa20_ref.go
│   │   │   └── salsa_test.go
│   │   ├── salsa20.go
│   │   └── salsa20_test.go
│   ├── scrypt
│   │   ├── example_test.go
│   │   ├── scrypt.go
│   │   └── scrypt_test.go
│   ├── sha3
│   │   ├── doc.go
│   │   ├── hashes_generic.go
│   │   ├── hashes.go
│   │   ├── keccakf_amd64.go
│   │   ├── keccakf_amd64.s
│   │   ├── keccakf.go
│   │   ├── register.go
│   │   ├── sha3.go
│   │   ├── sha3_s390x.go
│   │   ├── sha3_s390x.s
│   │   ├── sha3_test.go
│   │   ├── shake_generic.go
│   │   ├── shake.go
│   │   ├── testdata
│   │   │   └── keccakKats.json.deflate
│   │   ├── xor_generic.go
│   │   ├── xor.go
│   │   └── xor_unaligned.go
│   ├── ssh
│   │   ├── agent
│   │   │   ├── client.go
│   │   │   ├── client_test.go
│   │   │   ├── example_test.go
│   │   │   ├── forward.go
│   │   │   ├── keyring.go
│   │   │   ├── keyring_test.go
│   │   │   ├── server.go
│   │   │   ├── server_test.go
│   │   │   └── testdata_test.go
│   │   ├── benchmark_test.go
│   │   ├── buffer.go
│   │   ├── buffer_test.go
│   │   ├── certs.go
│   │   ├── certs_test.go
│   │   ├── channel.go
│   │   ├── cipher.go
│   │   ├── cipher_test.go
│   │   ├── client_auth.go
│   │   ├── client_auth_test.go
│   │   ├── client.go
│   │   ├── client_test.go
│   │   ├── common.go
│   │   ├── common_test.go
│   │   ├── connection.go
│   │   ├── doc.go
│   │   ├── example_test.go
│   │   ├── handshake.go
│   │   ├── handshake_test.go
│   │   ├── kex.go
│   │   ├── kex_test.go
│   │   ├── keys.go
│   │   ├── keys_test.go
│   │   ├── knownhosts
│   │   │   ├── knownhosts.go
│   │   │   └── knownhosts_test.go
│   │   ├── mac.go
│   │   ├── mempipe_test.go
│   │   ├── messages.go
│   │   ├── messages_test.go
│   │   ├── mux.go
│   │   ├── mux_test.go
│   │   ├── server.go
│   │   ├── session.go
│   │   ├── session_test.go
│   │   ├── ssh_gss.go
│   │   ├── ssh_gss_test.go
│   │   ├── streamlocal.go
│   │   ├── tcpip.go
│   │   ├── tcpip_test.go
│   │   ├── terminal
│   │   │   ├── terminal.go
│   │   │   ├── terminal_test.go
│   │   │   ├── util_aix.go
│   │   │   ├── util_bsd.go
│   │   │   ├── util.go
│   │   │   ├── util_linux.go
│   │   │   ├── util_plan9.go
│   │   │   ├── util_solaris.go
│   │   │   └── util_windows.go
│   │   ├── test
│   │   │   ├── agent_unix_test.go
│   │   │   ├── banner_test.go
│   │   │   ├── cert_test.go
│   │   │   ├── dial_unix_test.go
│   │   │   ├── doc.go
│   │   │   ├── forward_unix_test.go
│   │   │   ├── multi_auth_test.go
│   │   │   ├── session_test.go
│   │   │   ├── sshd_test_pw.c
│   │   │   ├── testdata_test.go
│   │   │   └── test_unix_test.go
│   │   ├── testdata
│   │   │   ├── doc.go
│   │   │   └── keys.go
│   │   ├── testdata_test.go
│   │   ├── transport.go
│   │   └── transport_test.go
│   ├── tea
│   │   ├── cipher.go
│   │   └── tea_test.go
│   ├── twofish
│   │   ├── twofish.go
│   │   └── twofish_test.go
│   ├── xtea
│   │   ├── block.go
│   │   ├── cipher.go
│   │   └── xtea_test.go
│   └── xts
│       ├── xts.go
│       └── xts_test.go
├── exp
│   ├── apidiff
│   │   ├── apidiff.go
│   │   ├── apidiff_test.go
│   │   ├── compatibility.go
│   │   ├── correspondence.go
│   │   ├── messageset.go
│   │   ├── README.md
│   │   ├── report.go
│   │   └── testdata
│   │       ├── exported_fields
│   │       │   └── ef.go
│   │       └── tests.go
│   ├── AUTHORS
│   ├── cmd
│   │   ├── apidiff
│   │   │   └── main.go
│   │   ├── macos-roots-test
│   │   │   ├── main.go
│   │   │   ├── root_cgo_darwin.go
│   │   │   ├── root_darwin.go
│   │   │   └── root_nocgo_darwin.go
│   │   └── modgraphviz
│   │       ├── main.go
│   │       └── main_test.go
│   ├── codereview.cfg
│   ├── CONTRIBUTING.md
│   ├── CONTRIBUTORS
│   ├── ebnf
│   │   ├── ebnf.go
│   │   ├── ebnf_test.go
│   │   └── parser.go
│   ├── ebnflint
│   │   ├── doc.go
│   │   ├── ebnflint.go
│   │   └── ebnflint_test.go
│   ├── errors
│   │   ├── errors.go
│   │   ├── errors_test.go
│   │   ├── example_test.go
│   │   ├── fmt
│   │   │   ├── adaptor.go
│   │   │   ├── doc.go
│   │   │   ├── errors.go
│   │   │   ├── errors_test.go
│   │   │   ├── example_test.go
│   │   │   ├── export_test.go
│   │   │   ├── fmt_test.go
│   │   │   ├── format_example_test.go
│   │   │   ├── format.go
│   │   │   ├── print.go
│   │   │   ├── scan.go
│   │   │   ├── scan_test.go
│   │   │   └── stringer_test.go
│   │   ├── format.go
│   │   ├── frame.go
│   │   ├── go.mod
│   │   ├── internal
│   │   │   └── internal.go
│   │   ├── stack_test.go
│   │   ├── wrap.go
│   │   └── wrap_test.go
│   ├── fsnotify
│   │   └── README.txt
│   ├── go.mod
│   ├── go.sum
│   ├── inotify
│   │   └── README.txt
│   ├── io
│   │   ├── i2c
│   │   │   ├── devfs.go
│   │   │   ├── devfs_nonlinux.go
│   │   │   ├── driver
│   │   │   │   └── driver.go
│   │   │   ├── example
│   │   │   │   └── displayip
│   │   │   │       └── main.go
│   │   │   ├── example_test.go
│   │   │   ├── i2c.go
│   │   │   └── i2c_test.go
│   │   └── spi
│   │       ├── devfs.go
│   │       ├── devfs_nonlinux.go
│   │       ├── driver
│   │       │   └── driver.go
│   │       ├── example_test.go
│   │       └── spi.go
│   ├── LICENSE
│   ├── mmap
│   │   ├── manual_test_program.go
│   │   ├── mmap_other.go
│   │   ├── mmap_test.go
│   │   ├── mmap_unix.go
│   │   ├── mmap_windows_386.go
│   │   ├── mmap_windows_amd64.go
│   │   └── mmap_windows.go
│   ├── PATENTS
│   ├── rand
│   │   ├── arith128_test.go
│   │   ├── example_test.go
│   │   ├── exp.go
│   │   ├── modulo_test.go
│   │   ├── normal.go
│   │   ├── race_test.go
│   │   ├── rand.go
│   │   ├── rand_test.go
│   │   ├── regress_test.go
│   │   ├── rng.go
│   │   ├── uint64_fallback.go
│   │   ├── uint64.go
│   │   └── zipf.go
│   ├── README.md
│   ├── shiny
│   │   ├── driver
│   │   │   ├── driver_darwin.go
│   │   │   ├── driver_fallback.go
│   │   │   ├── driver.go
│   │   │   ├── driver_windows.go
│   │   │   ├── driver_x11.go
│   │   │   ├── gldriver
│   │   │   │   ├── buffer.go
│   │   │   │   ├── cocoa.go
│   │   │   │   ├── cocoa.m
│   │   │   │   ├── context.go
│   │   │   │   ├── egl.go
│   │   │   │   ├── gldriver.go
│   │   │   │   ├── other.go
│   │   │   │   ├── screen.go
│   │   │   │   ├── texture.go
│   │   │   │   ├── win32.go
│   │   │   │   ├── window.go
│   │   │   │   ├── x11.c
│   │   │   │   └── x11.go
│   │   │   ├── internal
│   │   │   │   ├── drawer
│   │   │   │   │   └── drawer.go
│   │   │   │   ├── errscreen
│   │   │   │   │   └── errscreen.go
│   │   │   │   ├── event
│   │   │   │   │   └── event.go
│   │   │   │   ├── lifecycler
│   │   │   │   │   └── lifecycler.go
│   │   │   │   ├── swizzle
│   │   │   │   │   ├── swizzle_amd64.go
│   │   │   │   │   ├── swizzle_amd64.s
│   │   │   │   │   ├── swizzle_common.go
│   │   │   │   │   ├── swizzle_other.go
│   │   │   │   │   └── swizzle_test.go
│   │   │   │   ├── win32
│   │   │   │   │   ├── key.go
│   │   │   │   │   ├── syscall.go
│   │   │   │   │   ├── syscall_windows.go
│   │   │   │   │   ├── win32.go
│   │   │   │   │   └── zsyscall_windows.go
│   │   │   │   └── x11key
│   │   │   │       ├── gen.go
│   │   │   │       ├── table.go
│   │   │   │       └── x11key.go
│   │   │   ├── mtldriver
│   │   │   │   ├── buffer.go
│   │   │   │   ├── internal
│   │   │   │   │   ├── appkit
│   │   │   │   │   │   ├── appkit.go
│   │   │   │   │   │   ├── appkit.h
│   │   │   │   │   │   └── appkit.m
│   │   │   │   │   └── coreanim
│   │   │   │   │       ├── coreanim.go
│   │   │   │   │       ├── coreanim.h
│   │   │   │   │       └── coreanim.m
│   │   │   │   ├── mtldriver.go
│   │   │   │   ├── screen.go
│   │   │   │   ├── texture.go
│   │   │   │   └── window.go
│   │   │   ├── mtldriver_darwin.go
│   │   │   ├── windriver
│   │   │   │   ├── buffer.go
│   │   │   │   ├── doc.go
│   │   │   │   ├── other.go
│   │   │   │   ├── screen.go
│   │   │   │   ├── syscall.go
│   │   │   │   ├── syscall_windows.go
│   │   │   │   ├── texture.go
│   │   │   │   ├── window.go
│   │   │   │   ├── windraw.go
│   │   │   │   ├── windriver.go
│   │   │   │   └── zsyscall_windows.go
│   │   │   └── x11driver
│   │   │       ├── buffer.go
│   │   │       ├── screen.go
│   │   │       ├── shm_linux_ipc.go
│   │   │       ├── shm_openbsd_syscall.go
│   │   │       ├── shm_other.go
│   │   │       ├── shm_shmopen_syscall.go
│   │   │       ├── texture.go
│   │   │       ├── window.go
│   │   │       └── x11driver.go
│   │   ├── example
│   │   │   ├── basic
│   │   │   │   └── main.go
│   │   │   ├── basicgl
│   │   │   │   └── main.go
│   │   │   ├── fluid
│   │   │   │   └── main.go
│   │   │   ├── goban
│   │   │   │   ├── asset
│   │   │   │   │   ├── blackstone01.jpg
│   │   │   │   │   ├── blackstone02.jpg
│   │   │   │   │   ├── blackstone03.jpg
│   │   │   │   │   ├── blackstone04.jpg
│   │   │   │   │   ├── blackstone05.jpg
│   │   │   │   │   ├── blackstone06.jpg
│   │   │   │   │   ├── blackstone07.jpg
│   │   │   │   │   ├── blackstone08.jpg
│   │   │   │   │   ├── blackstone09.jpg
│   │   │   │   │   ├── blackstone10.jpg
│   │   │   │   │   ├── blackstone11.jpg
│   │   │   │   │   ├── blackstone12.jpg
│   │   │   │   │   ├── blackstone13.jpg
│   │   │   │   │   ├── goboard.jpg
│   │   │   │   │   ├── resize.go
│   │   │   │   │   ├── whitestone01.jpg
│   │   │   │   │   ├── whitestone02.jpg
│   │   │   │   │   ├── whitestone03.jpg
│   │   │   │   │   ├── whitestone04.jpg
│   │   │   │   │   ├── whitestone05.jpg
│   │   │   │   │   ├── whitestone06.jpg
│   │   │   │   │   ├── whitestone07.jpg
│   │   │   │   │   ├── whitestone08.jpg
│   │   │   │   │   ├── whitestone09.jpg
│   │   │   │   │   ├── whitestone10.jpg
│   │   │   │   │   └── whitestone11.jpg
│   │   │   │   ├── board.go
│   │   │   │   ├── main.go
│   │   │   │   ├── xy.go
│   │   │   │   └── xy_test.go
│   │   │   ├── icongallery
│   │   │   │   └── main.go
│   │   │   ├── imageview
│   │   │   │   └── main.go
│   │   │   ├── layout
│   │   │   │   └── main.go
│   │   │   ├── textedit
│   │   │   │   └── main.go
│   │   │   ├── tile
│   │   │   │   └── main.go
│   │   │   └── widgetgallery
│   │   │       └── main.go
│   │   ├── gesture
│   │   │   └── gesture.go
│   │   ├── iconvg
│   │   │   ├── buffer.go
│   │   │   ├── buffer_test.go
│   │   │   ├── color.go
│   │   │   ├── decode.go
│   │   │   ├── decode_test.go
│   │   │   ├── doc.go
│   │   │   ├── encode.go
│   │   │   ├── encode_test.go
│   │   │   ├── example_test.go
│   │   │   ├── iconvg.go
│   │   │   ├── internal
│   │   │   │   └── gradient
│   │   │   │       └── gradient.go
│   │   │   ├── rasterizer.go
│   │   │   └── testdata
│   │   │       ├── action-info.hires.ivg
│   │   │       ├── action-info.hires.ivg.disassembly
│   │   │       ├── action-info.hires.png
│   │   │       ├── action-info.lores.ivg
│   │   │       ├── action-info.lores.ivg.disassembly
│   │   │       ├── action-info.lores.png
│   │   │       ├── action-info.svg
│   │   │       ├── arcs.ivg
│   │   │       ├── arcs.ivg.disassembly
│   │   │       ├── arcs.png
│   │   │       ├── blank.ivg
│   │   │       ├── blank.ivg.disassembly
│   │   │       ├── blank.png
│   │   │       ├── cowbell.ivg
│   │   │       ├── cowbell.ivg.disassembly
│   │   │       ├── cowbell.png
│   │   │       ├── cowbell.svg
│   │   │       ├── elliptical.ivg
│   │   │       ├── elliptical.ivg.disassembly
│   │   │       ├── elliptical.png
│   │   │       ├── favicon.ivg
│   │   │       ├── favicon.ivg.disassembly
│   │   │       ├── favicon.pink.png
│   │   │       ├── favicon.png
│   │   │       ├── favicon.svg
│   │   │       ├── gradient.ivg
│   │   │       ├── gradient.ivg.disassembly
│   │   │       ├── gradient.png
│   │   │       ├── lod-polygon.64.png
│   │   │       ├── lod-polygon.ivg
│   │   │       ├── lod-polygon.ivg.disassembly
│   │   │       ├── lod-polygon.png
│   │   │       ├── README
│   │   │       ├── video-005.jpeg
│   │   │       ├── video-005.primitive.ivg
│   │   │       ├── video-005.primitive.ivg.disassembly
│   │   │       ├── video-005.primitive.png
│   │   │       └── video-005.primitive.svg
│   │   ├── imageutil
│   │   │   ├── imageutil.go
│   │   │   └── imageutil_test.go
│   │   ├── materialdesign
│   │   │   ├── colornames
│   │   │   │   ├── colornames.go
│   │   │   │   ├── colornames_test.go
│   │   │   │   ├── gen.go
│   │   │   │   └── table.go
│   │   │   └── icons
│   │   │       ├── data.go
│   │   │       ├── data_test.go
│   │   │       ├── gen.go
│   │   │       ├── icons.go
│   │   │       └── icons_test.go
│   │   ├── screen
│   │   │   ├── screen.go
│   │   │   └── screen_test.go
│   │   ├── text
│   │   │   ├── caret.go
│   │   │   ├── example_test.go
│   │   │   ├── text.go
│   │   │   └── text_test.go
│   │   ├── unit
│   │   │   └── unit.go
│   │   ├── vendor
│   │   │   └── github.com
│   │   │       └── BurntSushi
│   │   │           └── xgb
│   │   │               ├── auth.go
│   │   │               ├── AUTHORS
│   │   │               ├── conn.go
│   │   │               ├── CONTRIBUTORS
│   │   │               ├── cookie.go
│   │   │               ├── doc.go
│   │   │               ├── help.go
│   │   │               ├── LICENSE
│   │   │               ├── README
│   │   │               ├── README.vendor
│   │   │               ├── render
│   │   │               │   └── render.go
│   │   │               ├── shm
│   │   │               │   └── shm.go
│   │   │               ├── sync.go
│   │   │               ├── xgb.go
│   │   │               └── xproto
│   │   │                   ├── xproto.go
│   │   │                   └── xproto_test.go
│   │   └── widget
│   │       ├── flex
│   │       │   ├── flex.go
│   │       │   └── flex_test.go
│   │       ├── flow.go
│   │       ├── glwidget
│   │       │   └── glwidget.go
│   │       ├── image.go
│   │       ├── label.go
│   │       ├── node
│   │       │   └── node.go
│   │       ├── padder.go
│   │       ├── sheet.go
│   │       ├── sizer.go
│   │       ├── space.go
│   │       ├── text.go
│   │       ├── theme
│   │       │   ├── theme.go
│   │       │   └── theme_test.go
│   │       ├── uniform.go
│   │       └── widget.go
│   ├── shootout
│   │   ├── binary-tree.c
│   │   ├── binary-tree-freelist.go
│   │   ├── binary-tree-freelist.txt
│   │   ├── binary-tree.go
│   │   ├── binary-tree.txt
│   │   ├── chameneosredux.c
│   │   ├── chameneosredux.go
│   │   ├── chameneosredux.txt
│   │   ├── fannkuch.c
│   │   ├── fannkuch.go
│   │   ├── fannkuch-parallel.go
│   │   ├── fannkuch-parallel.txt
│   │   ├── fannkuch.txt
│   │   ├── fasta-1000.txt
│   │   ├── fasta.c
│   │   ├── fasta.go
│   │   ├── fasta.txt
│   │   ├── k-nucleotide.c
│   │   ├── k-nucleotide.go
│   │   ├── k-nucleotide-parallel.go
│   │   ├── k-nucleotide-parallel.txt
│   │   ├── k-nucleotide.txt
│   │   ├── mandelbrot.c
│   │   ├── mandelbrot.go
│   │   ├── mandelbrot.txt
│   │   ├── meteor-contest.c
│   │   ├── meteor-contest.go
│   │   ├── meteor-contest.txt
│   │   ├── nbody.c
│   │   ├── nbody.go
│   │   ├── nbody.txt
│   │   ├── pidigits.c
│   │   ├── pidigits.go
│   │   ├── pidigits.txt
│   │   ├── README
│   │   ├── regex-dna.c
│   │   ├── regex-dna.go
│   │   ├── regex-dna-parallel.go
│   │   ├── regex-dna-parallel.txt
│   │   ├── regex-dna.txt
│   │   ├── reverse-complement.c
│   │   ├── reverse-complement.go
│   │   ├── reverse-complement.txt
│   │   ├── spectral-norm.c
│   │   ├── spectral-norm.go
│   │   ├── spectral-norm-parallel.go
│   │   ├── spectral-norm.txt
│   │   ├── threadring.c
│   │   ├── threadring.go
│   │   ├── threadring.txt
│   │   ├── timing.log
│   │   └── timing.sh
│   ├── sumdb
│   │   ├── go.mod
│   │   ├── go.sum
│   │   ├── gosumcheck
│   │   │   ├── main.go
│   │   │   ├── test.bash
│   │   │   └── test.sum
│   │   └── internal
│   │       ├── note
│   │       │   ├── example_test.go
│   │       │   ├── note.go
│   │       │   └── note_test.go
│   │       ├── sumweb
│   │       │   ├── cache.go
│   │       │   ├── client.go
│   │       │   ├── client_test.go
│   │       │   ├── encode.go
│   │       │   ├── encode_test.go
│   │       │   ├── server.go
│   │       │   └── test.go
│   │       ├── tkv
│   │       │   ├── tkv.go
│   │       │   └── tkvtest
│   │       │       ├── mem.go
│   │       │       ├── mem_test.go
│   │       │       └── test.go
│   │       └── tlog
│   │           ├── ct_test.go
│   │           ├── note.go
│   │           ├── note_test.go
│   │           ├── tile.go
│   │           ├── tlog.go
│   │           └── tlog_test.go
│   ├── utf8string
│   │   ├── string.go
│   │   └── string_test.go
│   └── winfsnotify
│       ├── winfsnotify.go
│       └── winfsnotify_test.go
├── image
│   ├── AUTHORS
│   ├── bmp
│   │   ├── reader.go
│   │   ├── reader_test.go
│   │   ├── writer.go
│   │   └── writer_test.go
│   ├── ccitt
│   │   ├── gen.go
│   │   ├── reader.go
│   │   ├── reader_test.go
│   │   ├── table.go
│   │   ├── table_test.go
│   │   ├── testdata
│   │   │   ├── bw-gopher-aligned.ccitt_group3
│   │   │   ├── bw-gopher-aligned.ccitt_group4
│   │   │   ├── bw-gopher.ccitt_group3
│   │   │   ├── bw-gopher.ccitt_group4
│   │   │   ├── bw-gopher-inverted-aligned.ccitt_group3
│   │   │   ├── bw-gopher-inverted-aligned.ccitt_group4
│   │   │   ├── bw-gopher-inverted.ccitt_group3
│   │   │   ├── bw-gopher-inverted.ccitt_group4
│   │   │   └── bw-gopher.png
│   │   ├── writer.go
│   │   └── writer_test.go
│   ├── cmd
│   │   └── webp-manual-test
│   │       └── main.go
│   ├── codereview.cfg
│   ├── colornames
│   │   ├── colornames.go
│   │   ├── colornames_test.go
│   │   ├── gen.go
│   │   └── table.go
│   ├── CONTRIBUTING.md
│   ├── CONTRIBUTORS
│   ├── draw
│   │   ├── draw.go
│   │   ├── example_test.go
│   │   ├── gen.go
│   │   ├── impl.go
│   │   ├── scale.go
│   │   ├── scale_test.go
│   │   └── stdlib_test.go
│   ├── example
│   │   └── font
│   │       └── main.go
│   ├── font
│   │   ├── basicfont
│   │   │   ├── basicfont.go
│   │   │   ├── basicfont_test.go
│   │   │   ├── data.go
│   │   │   └── gen.go
│   │   ├── font.go
│   │   ├── font_test.go
│   │   ├── gofont
│   │   │   ├── gen.go
│   │   │   ├── gobold
│   │   │   │   └── data.go
│   │   │   ├── gobolditalic
│   │   │   │   └── data.go
│   │   │   ├── goitalic
│   │   │   │   └── data.go
│   │   │   ├── gomedium
│   │   │   │   └── data.go
│   │   │   ├── gomediumitalic
│   │   │   │   └── data.go
│   │   │   ├── gomono
│   │   │   │   └── data.go
│   │   │   ├── gomonobold
│   │   │   │   └── data.go
│   │   │   ├── gomonobolditalic
│   │   │   │   └── data.go
│   │   │   ├── gomonoitalic
│   │   │   │   └── data.go
│   │   │   ├── goregular
│   │   │   │   └── data.go
│   │   │   ├── gosmallcaps
│   │   │   │   └── data.go
│   │   │   ├── gosmallcapsitalic
│   │   │   │   └── data.go
│   │   │   └── ttfs
│   │   │       ├── Go-Bold-Italic.ttf
│   │   │       ├── Go-Bold.ttf
│   │   │       ├── Go-Italic.ttf
│   │   │       ├── Go-Medium-Italic.ttf
│   │   │       ├── Go-Medium.ttf
│   │   │       ├── Go-Mono-Bold-Italic.ttf
│   │   │       ├── Go-Mono-Bold.ttf
│   │   │       ├── Go-Mono-Italic.ttf
│   │   │       ├── Go-Mono.ttf
│   │   │       ├── Go-Regular.ttf
│   │   │       ├── Go-Smallcaps-Italic.ttf
│   │   │       ├── Go-Smallcaps.ttf
│   │   │       └── README
│   │   ├── inconsolata
│   │   │   ├── bold8x16.go
│   │   │   ├── inconsolata.go
│   │   │   └── regular8x16.go
│   │   ├── opentype
│   │   │   ├── face.go
│   │   │   ├── face_test.go
│   │   │   └── opentype.go
│   │   ├── plan9font
│   │   │   ├── example_test.go
│   │   │   ├── plan9font.go
│   │   │   └── plan9font_test.go
│   │   ├── sfnt
│   │   │   ├── cmap.go
│   │   │   ├── data.go
│   │   │   ├── example_test.go
│   │   │   ├── gen.go
│   │   │   ├── gpos.go
│   │   │   ├── kern_test.go
│   │   │   ├── postscript.go
│   │   │   ├── proprietary_test.go
│   │   │   ├── sfnt.go
│   │   │   ├── sfnt_test.go
│   │   │   └── truetype.go
│   │   └── testdata
│   │       ├── CFFTest.otf
│   │       ├── CFFTest.sfd
│   │       ├── cmapTest.sfd
│   │       ├── cmapTest.ttf
│   │       ├── fixed
│   │       │   ├── 7x13.0000
│   │       │   ├── 7x13.0100
│   │       │   ├── 7x13.0200
│   │       │   ├── 7x13.0300
│   │       │   ├── 7x13.0400
│   │       │   ├── 7x13.0500
│   │       │   ├── 7x13.0E00
│   │       │   ├── 7x13.1000
│   │       │   ├── 7x13.1600
│   │       │   ├── 7x13.1E00
│   │       │   ├── 7x13.1F00
│   │       │   ├── 7x13.2000
│   │       │   ├── 7x13.2100
│   │       │   ├── 7x13.2200
│   │       │   ├── 7x13.2300
│   │       │   ├── 7x13.2400
│   │       │   ├── 7x13.2500
│   │       │   ├── 7x13.2600
│   │       │   ├── 7x13.2700
│   │       │   ├── 7x13.2800
│   │       │   ├── 7x13.2A00
│   │       │   ├── 7x13.3000
│   │       │   ├── 7x13.FB00
│   │       │   ├── 7x13.FE00
│   │       │   ├── 7x13.FF00
│   │       │   ├── README
│   │       │   └── unicode.7x13.font
│   │       ├── glyfTest.sfd
│   │       ├── glyfTest.ttf
│   │       └── README
│   ├── go.mod
│   ├── go.sum
│   ├── LICENSE
│   ├── math
│   │   ├── f32
│   │   │   └── f32.go
│   │   ├── f64
│   │   │   └── f64.go
│   │   └── fixed
│   │       ├── fixed.go
│   │       └── fixed_test.go
│   ├── PATENTS
│   ├── README.md
│   ├── riff
│   │   ├── example_test.go
│   │   ├── riff.go
│   │   └── riff_test.go
│   ├── testdata
│   │   ├── blue-purple-pink-large.lossless.webp
│   │   ├── blue-purple-pink-large.no-filter.lossy.webp
│   │   ├── blue-purple-pink-large.no-filter.lossy.webp.ycbcr.png
│   │   ├── blue-purple-pink-large.normal-filter.lossy.webp
│   │   ├── blue-purple-pink-large.normal-filter.lossy.webp.ycbcr.png
│   │   ├── blue-purple-pink-large.png
│   │   ├── blue-purple-pink-large.simple-filter.lossy.webp
│   │   ├── blue-purple-pink-large.simple-filter.lossy.webp.ycbcr.png
│   │   ├── blue-purple-pink.lossless.webp
│   │   ├── blue-purple-pink.lossy.webp
│   │   ├── blue-purple-pink.lossy.webp.ycbcr.png
│   │   ├── blue-purple-pink.lzwcompressed.tiff
│   │   ├── blue-purple-pink.png
│   │   ├── bw-deflate.tiff
│   │   ├── bw-gopher_ccittGroup3.tiff
│   │   ├── bw-gopher_ccittGroup4.tiff
│   │   ├── bw-gopher.png
│   │   ├── bw-packbits.tiff
│   │   ├── bw-uncompressed.tiff
│   │   ├── colormap.bmp
│   │   ├── colormap.png
│   │   ├── gopher-doc.1bpp.lossless.webp
│   │   ├── gopher-doc.1bpp.png
│   │   ├── gopher-doc.2bpp.lossless.webp
│   │   ├── gopher-doc.2bpp.png
│   │   ├── gopher-doc.4bpp.lossless.webp
│   │   ├── gopher-doc.4bpp.png
│   │   ├── gopher-doc.8bpp.lossless.webp
│   │   ├── gopher-doc.8bpp.png
│   │   ├── go-turns-two-14x18.png
│   │   ├── go-turns-two-280x360.jpeg
│   │   ├── go-turns-two-down-ab.png
│   │   ├── go-turns-two-down-bl.png
│   │   ├── go-turns-two-down-cr.png
│   │   ├── go-turns-two-down-nn.png
│   │   ├── go-turns-two-rotate-ab.png
│   │   ├── go-turns-two-rotate-bl.png
│   │   ├── go-turns-two-rotate-cr.png
│   │   ├── go-turns-two-rotate-nn.png
│   │   ├── go-turns-two-up-ab.png
│   │   ├── go-turns-two-up-bl.png
│   │   ├── go-turns-two-up-cr.png
│   │   ├── go-turns-two-up-nn.png
│   │   ├── no_compress.tiff
│   │   ├── no_rps.tiff
│   │   ├── testpattern.png
│   │   ├── tux.lossless.webp
│   │   ├── tux.png
│   │   ├── tux-rotate-ab.png
│   │   ├── tux-rotate-bl.png
│   │   ├── tux-rotate-cr.png
│   │   ├── tux-rotate-nn.png
│   │   ├── video-001-16bit.tiff
│   │   ├── video-001.bmp
│   │   ├── video-001-gray-16bit.tiff
│   │   ├── video-001-gray.tiff
│   │   ├── video-001.lossy.webp
│   │   ├── video-001.lossy.webp.ycbcr.png
│   │   ├── video-001-paletted.tiff
│   │   ├── video-001.png
│   │   ├── video-001-strip-64.tiff
│   │   ├── video-001.tiff
│   │   ├── video-001-tile-64x64.tiff
│   │   ├── video-001-uncompressed.tiff
│   │   ├── yellow_rose.lossless.webp
│   │   ├── yellow_rose.lossy.webp
│   │   ├── yellow_rose.lossy.webp.ycbcr.png
│   │   ├── yellow_rose.lossy-with-alpha.webp
│   │   ├── yellow_rose.lossy-with-alpha.webp.nycbcra.png
│   │   ├── yellow_rose.png
│   │   ├── yellow_rose-small.bmp
│   │   ├── yellow_rose-small.png
│   │   ├── yellow_rose-small-v5.bmp
│   │   └── yellow_rose-small-v5.png
│   ├── tiff
│   │   ├── buffer.go
│   │   ├── buffer_test.go
│   │   ├── compress.go
│   │   ├── consts.go
│   │   ├── fuzz.go
│   │   ├── lzw
│   │   │   └── reader.go
│   │   ├── reader.go
│   │   ├── reader_test.go
│   │   ├── writer.go
│   │   └── writer_test.go
│   ├── vector
│   │   ├── acc_amd64.go
│   │   ├── acc_amd64.s
│   │   ├── acc_other.go
│   │   ├── acc_test.go
│   │   ├── gen_acc_amd64.s.tmpl
│   │   ├── gen.go
│   │   ├── raster_fixed.go
│   │   ├── raster_floating.go
│   │   ├── vector.go
│   │   └── vector_test.go
│   ├── vp8
│   │   ├── decode.go
│   │   ├── filter.go
│   │   ├── idct.go
│   │   ├── partition.go
│   │   ├── predfunc.go
│   │   ├── pred.go
│   │   ├── quant.go
│   │   ├── reconstruct.go
│   │   └── token.go
│   ├── vp8l
│   │   ├── decode.go
│   │   ├── huffman.go
│   │   └── transform.go
│   └── webp
│       ├── decode.go
│       ├── decode_test.go
│       └── doc.go
├── mobile
│   ├── app
│   │   ├── android.c
│   │   ├── android.go
│   │   ├── app.go
│   │   ├── app_test.go
│   │   ├── darwin_desktop.go
│   │   ├── darwin_desktop.m
│   │   ├── darwin_ios.go
│   │   ├── darwin_ios.m
│   │   ├── doc.go
│   │   ├── GoNativeActivity.java
│   │   ├── internal
│   │   │   ├── apptest
│   │   │   │   └── apptest.go
│   │   │   ├── callfn
│   │   │   │   ├── callfn_386.s
│   │   │   │   ├── callfn_amd64.s
│   │   │   │   ├── callfn_arm64.s
│   │   │   │   ├── callfn_arm.s
│   │   │   │   └── callfn.go
│   │   │   └── testapp
│   │   │       ├── AndroidManifest.xml
│   │   │       └── testapp.go
│   │   ├── shiny.go
│   │   ├── x11.c
│   │   └── x11.go
│   ├── asset
│   │   ├── asset_android.go
│   │   ├── asset_darwin_armx.go
│   │   ├── asset_desktop.go
│   │   ├── asset.go
│   │   └── doc.go
│   ├── AUTHORS
│   ├── bind
│   │   ├── bind.go
│   │   ├── bind_test.go
│   │   ├── genclasses.go
│   │   ├── gen.go
│   │   ├── gengo.go
│   │   ├── genjava.go
│   │   ├── genobjc.go
│   │   ├── genobjcw.go
│   │   ├── java
│   │   │   ├── ClassesTest.java
│   │   │   ├── context_android.c
│   │   │   ├── context_android.go
│   │   │   ├── CustomPkgTest.java
│   │   │   ├── doc.go
│   │   │   ├── seq_android.c.support
│   │   │   ├── seq_android.go.support
│   │   │   ├── seq_android.h
│   │   │   ├── SeqBench.java
│   │   │   ├── Seq.java
│   │   │   ├── seq_test.go
│   │   │   └── SeqTest.java
│   │   ├── objc
│   │   │   ├── doc.go
│   │   │   ├── ref.h
│   │   │   ├── SeqBench.m
│   │   │   ├── SeqCustom.m
│   │   │   ├── seq_darwin.go.support
│   │   │   ├── seq_darwin.h
│   │   │   ├── seq_darwin.m.support
│   │   │   ├── seq_test.go
│   │   │   ├── SeqTest.m
│   │   │   └── SeqWrappers.m
│   │   ├── printer.go
│   │   ├── seq
│   │   │   ├── ref.go
│   │   │   ├── seq.go
│   │   │   ├── string.go
│   │   │   └── string_test.go
│   │   ├── seq.go.support
│   │   ├── testdata
│   │   │   ├── basictypes.go
│   │   │   ├── basictypes.go.golden
│   │   │   ├── basictypes.java.c.golden
│   │   │   ├── basictypes.java.golden
│   │   │   ├── basictypes.java.h.golden
│   │   │   ├── basictypes.objc.go.h.golden
│   │   │   ├── basictypes.objc.h.golden
│   │   │   ├── basictypes.objc.m.golden
│   │   │   ├── benchmark
│   │   │   │   └── benchmark.go
│   │   │   ├── cgopkg
│   │   │   │   └── cgopkg.go
│   │   │   ├── classes.go
│   │   │   ├── classes.go.golden
│   │   │   ├── classes.java.c.golden
│   │   │   ├── classes.java.golden
│   │   │   ├── classes.java.h.golden
│   │   │   ├── customprefixEX.objc.go.h.golden
│   │   │   ├── customprefixEX.objc.h.golden
│   │   │   ├── customprefixEX.objc.m.golden
│   │   │   ├── customprefix.go
│   │   │   ├── customprefix.java.c.golden
│   │   │   ├── customprefix.java.golden
│   │   │   ├── customprefix.java.h.golden
│   │   │   ├── customprefix.objc.go.h.golden
│   │   │   ├── customprefix.objc.h.golden
│   │   │   ├── customprefix.objc.m.golden
│   │   │   ├── doc.go
│   │   │   ├── doc.go.golden
│   │   │   ├── doc.java.c.golden
│   │   │   ├── doc.java.golden
│   │   │   ├── doc.java.h.golden
│   │   │   ├── doc.objc.go.h.golden
│   │   │   ├── doc.objc.h.golden
│   │   │   ├── doc.objc.m.golden
│   │   │   ├── ignore.go
│   │   │   ├── ignore.go.golden
│   │   │   ├── ignore.java.c.golden
│   │   │   ├── ignore.java.golden
│   │   │   ├── ignore.java.h.golden
│   │   │   ├── ignore.objc.go.h.golden
│   │   │   ├── ignore.objc.h.golden
│   │   │   ├── ignore.objc.m.golden
│   │   │   ├── interfaces.go
│   │   │   ├── interfaces.go.golden
│   │   │   ├── interfaces.java.c.golden
│   │   │   ├── interfaces.java.golden
│   │   │   ├── interfaces.java.h.golden
│   │   │   ├── interfaces.objc.go.h.golden
│   │   │   ├── interfaces.objc.h.golden
│   │   │   ├── interfaces.objc.m.golden
│   │   │   ├── issue10788.go
│   │   │   ├── issue10788.go.golden
│   │   │   ├── issue10788.java.c.golden
│   │   │   ├── issue10788.java.golden
│   │   │   ├── issue10788.java.h.golden
│   │   │   ├── issue10788.objc.go.h.golden
│   │   │   ├── issue10788.objc.h.golden
│   │   │   ├── issue10788.objc.m.golden
│   │   │   ├── issue12328.go
│   │   │   ├── issue12328.go.golden
│   │   │   ├── issue12328.java.c.golden
│   │   │   ├── issue12328.java.golden
│   │   │   ├── issue12328.java.h.golden
│   │   │   ├── issue12328.objc.go.h.golden
│   │   │   ├── issue12328.objc.h.golden
│   │   │   ├── issue12328.objc.m.golden
│   │   │   ├── issue12403.go
│   │   │   ├── issue12403.go.golden
│   │   │   ├── issue12403.java.c.golden
│   │   │   ├── issue12403.java.golden
│   │   │   ├── issue12403.java.h.golden
│   │   │   ├── issue12403.objc.go.h.golden
│   │   │   ├── issue12403.objc.h.golden
│   │   │   ├── issue12403.objc.m.golden
│   │   │   ├── issue29559.go
│   │   │   ├── issue29559.go.golden
│   │   │   ├── issue29559.java.c.golden
│   │   │   ├── issue29559.java.golden
│   │   │   ├── issue29559.java.h.golden
│   │   │   ├── issue29559.objc.go.h.golden
│   │   │   ├── issue29559.objc.h.golden
│   │   │   ├── issue29559.objc.m.golden
│   │   │   ├── java.go
│   │   │   ├── java.go.golden
│   │   │   ├── java.java.c.golden
│   │   │   ├── java.java.golden
│   │   │   ├── java.java.h.golden
│   │   │   ├── keywords.go
│   │   │   ├── keywords.go.golden
│   │   │   ├── keywords.java.c.golden
│   │   │   ├── keywords.java.golden
│   │   │   ├── keywords.java.h.golden
│   │   │   ├── keywords.objc.go.h.golden
│   │   │   ├── keywords.objc.h.golden
│   │   │   ├── keywords.objc.m.golden
│   │   │   ├── objc.go
│   │   │   ├── objc.go.golden
│   │   │   ├── objcw.go
│   │   │   ├── objcw.go.golden
│   │   │   ├── structs.go
│   │   │   ├── structs.go.golden
│   │   │   ├── structs.java.c.golden
│   │   │   ├── structs.java.golden
│   │   │   ├── structs.java.h.golden
│   │   │   ├── structs.objc.go.h.golden
│   │   │   ├── structs.objc.h.golden
│   │   │   ├── structs.objc.m.golden
│   │   │   ├── testpkg
│   │   │   │   ├── assets
│   │   │   │   │   └── hello.txt
│   │   │   │   ├── javapkg
│   │   │   │   │   ├── classes.go
│   │   │   │   │   └── java.go
│   │   │   │   ├── objcpkg
│   │   │   │   │   ├── classes.go
│   │   │   │   │   └── objc.go
│   │   │   │   ├── secondpkg
│   │   │   │   │   └── secondpkg.go
│   │   │   │   ├── simplepkg
│   │   │   │   │   └── simplepkg.go
│   │   │   │   ├── tagged.go
│   │   │   │   ├── testpkg.go
│   │   │   │   └── unboundpkg
│   │   │   │       └── unboundpkg.go
│   │   │   ├── try.go
│   │   │   ├── try.go.golden
│   │   │   ├── try.java.c.golden
│   │   │   ├── try.java.golden
│   │   │   ├── try.java.h.golden
│   │   │   ├── try.objc.go.h.golden
│   │   │   ├── try.objc.h.golden
│   │   │   ├── try.objc.m.golden
│   │   │   ├── underscores.go
│   │   │   ├── underscores.go.golden
│   │   │   ├── underscores.java.c.golden
│   │   │   ├── underscores.java.golden
│   │   │   ├── underscores.java.h.golden
│   │   │   ├── underscores.objc.go.h.golden
│   │   │   ├── underscores.objc.h.golden
│   │   │   ├── underscores.objc.m.golden
│   │   │   ├── universe.golden
│   │   │   ├── universe.java.c.golden
│   │   │   ├── universe.java.golden
│   │   │   ├── universe.java.h.golden
│   │   │   ├── universe.objc.go.h.golden
│   │   │   ├── universe.objc.h.golden
│   │   │   ├── universe.objc.m.golden
│   │   │   ├── vars.go
│   │   │   ├── vars.go.golden
│   │   │   ├── vars.java.c.golden
│   │   │   ├── vars.java.golden
│   │   │   ├── vars.java.h.golden
│   │   │   ├── vars.objc.go.h.golden
│   │   │   ├── vars.objc.h.golden
│   │   │   └── vars.objc.m.golden
│   │   └── types.go
│   ├── cmd
│   │   ├── gobind
│   │   │   ├── doc.go
│   │   │   ├── gen.go
│   │   │   ├── gobind_test.go
│   │   │   └── main.go
│   │   └── gomobile
│   │       ├── binary_xml.go
│   │       ├── binary_xml_test.go
│   │       ├── bind_androidapp.go
│   │       ├── bind.go
│   │       ├── bind_iosapp.go
│   │       ├── bind_test.go
│   │       ├── build_androidapp.go
│   │       ├── build_darwin_test.go
│   │       ├── build.go
│   │       ├── build_iosapp.go
│   │       ├── build_test.go
│   │       ├── cert.go
│   │       ├── cert_test.go
│   │       ├── clean.go
│   │       ├── dex.go
│   │       ├── doc.go
│   │       ├── env.go
│   │       ├── env_test.go
│   │       ├── gendex.go
│   │       ├── init.go
│   │       ├── init_test.go
│   │       ├── install.go
│   │       ├── main.go
│   │       ├── manifest.go
│   │       ├── strings_flag.go
│   │       ├── version.go
│   │       ├── writer.go
│   │       └── writer_test.go
│   ├── codereview.cfg
│   ├── CONTRIBUTING.md
│   ├── CONTRIBUTORS
│   ├── doc
│   │   └── caution.png
│   ├── event
│   │   ├── key
│   │   │   ├── code_string.go
│   │   │   └── key.go
│   │   ├── lifecycle
│   │   │   └── lifecycle.go
│   │   ├── mouse
│   │   │   └── mouse.go
│   │   ├── paint
│   │   │   └── paint.go
│   │   ├── size
│   │   │   └── size.go
│   │   └── touch
│   │       └── touch.go
│   ├── example
│   │   ├── basic
│   │   │   ├── main.go
│   │   │   └── main_x.go
│   │   ├── bind
│   │   │   ├── android
│   │   │   │   ├── app
│   │   │   │   │   ├── build.gradle
│   │   │   │   │   └── src
│   │   │   │   │       └── main
│   │   │   │   │           ├── AndroidManifest.xml
│   │   │   │   │           ├── java
│   │   │   │   │           │   └── org
│   │   │   │   │           │       └── golang
│   │   │   │   │           │           └── example
│   │   │   │   │           │               └── bind
│   │   │   │   │           │                   └── MainActivity.java
│   │   │   │   │           └── res
│   │   │   │   │               ├── layout
│   │   │   │   │               │   └── activity_main.xml
│   │   │   │   │               └── values
│   │   │   │   │                   └── dimens.xml
│   │   │   │   ├── build.gradle
│   │   │   │   ├── README
│   │   │   │   └── settings.gradle
│   │   │   ├── hello
│   │   │   │   └── hello.go
│   │   │   └── ios
│   │   │       ├── bind
│   │   │       │   ├── AppDelegate.h
│   │   │       │   ├── AppDelegate.m
│   │   │       │   ├── Base.lproj
│   │   │       │   │   ├── LaunchScreen.xib
│   │   │       │   │   └── Main.storyboard
│   │   │       │   ├── Info.plist
│   │   │       │   ├── main.m
│   │   │       │   ├── ViewController.h
│   │   │       │   └── ViewController.m
│   │   │       ├── bind.xcodeproj
│   │   │       │   └── project.pbxproj
│   │   │       └── README
│   │   ├── flappy
│   │   │   ├── assets
│   │   │   │   ├── README
│   │   │   │   └── sprite.png
│   │   │   ├── game.go
│   │   │   ├── main.go
│   │   │   └── main_x.go
│   │   ├── ivy
│   │   │   ├── android
│   │   │   │   ├── app
│   │   │   │   │   ├── build.gradle
│   │   │   │   │   ├── proguard-rules.pro
│   │   │   │   │   └── src
│   │   │   │   │       ├── androidTest
│   │   │   │   │       │   └── java
│   │   │   │   │       │       └── org
│   │   │   │   │       │           └── golang
│   │   │   │   │       │               └── ivy
│   │   │   │   │       │                   └── ApplicationTest.java
│   │   │   │   │       └── main
│   │   │   │   │           ├── AndroidManifest.xml
│   │   │   │   │           ├── assets
│   │   │   │   │           │   ├── aboutivy.html
│   │   │   │   │           │   ├── demo.ivy
│   │   │   │   │           │   └── tape.html
│   │   │   │   │           ├── ic_launcher-web.png
│   │   │   │   │           ├── java
│   │   │   │   │           │   └── org
│   │   │   │   │           │       └── golang
│   │   │   │   │           │           └── ivy
│   │   │   │   │           │               ├── AboutIvy.java
│   │   │   │   │           │               ├── Help.java
│   │   │   │   │           │               └── MainActivity.java
│   │   │   │   │           └── res
│   │   │   │   │               ├── drawable
│   │   │   │   │               │   ├── circle_shape.xml
│   │   │   │   │               │   └── ivyabout.png
│   │   │   │   │               ├── drawable-hdpi
│   │   │   │   │               │   ├── actionbar_solid.png
│   │   │   │   │               │   └── ic_done_white_24dp.png
│   │   │   │   │               ├── drawable-mdpi
│   │   │   │   │               │   ├── actionbar_solid.png
│   │   │   │   │               │   └── ic_done_white_24dp.png
│   │   │   │   │               ├── drawable-xhdpi
│   │   │   │   │               │   ├── actionbar_solid.png
│   │   │   │   │               │   └── ic_done_white_24dp.png
│   │   │   │   │               ├── drawable-xxhdpi
│   │   │   │   │               │   ├── actionbar_solid.png
│   │   │   │   │               │   └── ic_done_white_24dp.png
│   │   │   │   │               ├── layout
│   │   │   │   │               │   ├── activity_about.xml
│   │   │   │   │               │   ├── activity_help.xml
│   │   │   │   │               │   └── activity_main.xml
│   │   │   │   │               ├── menu
│   │   │   │   │               │   ├── menu_about.xml
│   │   │   │   │               │   └── menu_main.xml
│   │   │   │   │               ├── mipmap-hdpi
│   │   │   │   │               │   └── ic_launcher.png
│   │   │   │   │               ├── mipmap-mdpi
│   │   │   │   │               │   └── ic_launcher.png
│   │   │   │   │               ├── mipmap-xhdpi
│   │   │   │   │               │   └── ic_launcher.png
│   │   │   │   │               ├── mipmap-xxhdpi
│   │   │   │   │               │   └── ic_launcher.png
│   │   │   │   │               ├── mipmap-xxxhdpi
│   │   │   │   │               │   └── ic_launcher.png
│   │   │   │   │               ├── values
│   │   │   │   │               │   ├── colors.xml
│   │   │   │   │               │   ├── dimens.xml
│   │   │   │   │               │   ├── strings.xml
│   │   │   │   │               │   └── styles.xml
│   │   │   │   │               └── values-w820dp
│   │   │   │   │                   ├── dimens.xml
│   │   │   │   │                   └── strings.xml
│   │   │   │   ├── build.gradle
│   │   │   │   ├── README
│   │   │   │   └── settings.gradle
│   │   │   └── ios
│   │   │       ├── ivy
│   │   │       │   ├── AppDelegate.h
│   │   │       │   ├── AppDelegate.m
│   │   │       │   ├── Base.lproj
│   │   │       │   │   └── Main.storyboard
│   │   │       │   ├── DocsController.h
│   │   │       │   ├── DocsController.m
│   │   │       │   ├── Images.xcassets
│   │   │       │   │   └── AppIcon.appiconset
│   │   │       │   │       ├── apple-touch-icon-120x120-1.png
│   │   │       │   │       ├── apple-touch-icon-120x120.png
│   │   │       │   │       ├── apple-touch-icon-152x152.png
│   │   │       │   │       ├── apple-touch-icon-76x76.png
│   │   │       │   │       ├── Contents.json
│   │   │       │   │       ├── ivy-ios-180.png
│   │   │       │   │       └── ivy-ios-80.png
│   │   │       │   ├── Info.plist
│   │   │       │   ├── IvyController.h
│   │   │       │   ├── IvyController.m
│   │   │       │   ├── Launch.storyboard
│   │   │       │   ├── main.m
│   │   │       │   ├── Suggestion.h
│   │   │       │   ├── Suggestion.m
│   │   │       │   └── tape.html
│   │   │       ├── ivy.xcodeproj
│   │   │       │   └── project.pbxproj
│   │   │       └── README.md
│   │   └── network
│   │       ├── AndroidManifest.xml
│   │       ├── main.go
│   │       └── main_x.go
│   ├── exp
│   │   ├── app
│   │   │   └── debug
│   │   │       └── fps.go
│   │   ├── audio
│   │   │   └── al
│   │   │       ├── al_android.go
│   │   │       ├── alc_android.go
│   │   │       ├── alc.go
│   │   │       ├── alc_notandroid.go
│   │   │       ├── al.go
│   │   │       ├── al_notandroid.go
│   │   │       └── const.go
│   │   ├── f32
│   │   │   ├── affine.go
│   │   │   ├── affine_test.go
│   │   │   ├── f32.go
│   │   │   ├── f32_test.go
│   │   │   ├── gen.go
│   │   │   ├── mat3.go
│   │   │   ├── mat4.go
│   │   │   ├── table.go
│   │   │   ├── vec3.go
│   │   │   └── vec4.go
│   │   ├── font
│   │   │   ├── doc.go
│   │   │   ├── font_android.go
│   │   │   ├── font_darwin.go
│   │   │   ├── font.go
│   │   │   ├── font_linux.go
│   │   │   └── font_test.go
│   │   ├── gl
│   │   │   └── glutil
│   │   │       ├── context_darwin_desktop.go
│   │   │       ├── context_x11.go
│   │   │       ├── doc.go
│   │   │       ├── glimage.go
│   │   │       ├── glimage_test.go
│   │   │       └── glutil.go
│   │   ├── README
│   │   ├── sensor
│   │   │   ├── android.c
│   │   │   ├── android.go
│   │   │   ├── darwin_armx.go
│   │   │   ├── darwin_armx.m
│   │   │   ├── notmobile.go
│   │   │   └── sensor.go
│   │   └── sprite
│   │       ├── clock
│   │       │   ├── clock.go
│   │       │   ├── tween.go
│   │       │   └── tween_test.go
│   │       ├── glsprite
│   │       │   └── glsprite.go
│   │       ├── portable
│   │       │   ├── affine_test.go
│   │       │   └── portable.go
│   │       └── sprite.go
│   ├── geom
│   │   └── geom.go
│   ├── gl
│   │   ├── consts.go
│   │   ├── dll_windows.go
│   │   ├── doc.go
│   │   ├── fn.go
│   │   ├── gendebug.go
│   │   ├── gldebug.go
│   │   ├── gl.go
│   │   ├── interface.go
│   │   ├── types_debug.go
│   │   ├── types_prod.go
│   │   ├── work.c
│   │   ├── work.go
│   │   ├── work.h
│   │   ├── work_other.go
│   │   ├── work_windows_386.s
│   │   ├── work_windows_amd64.s
│   │   └── work_windows.go
│   ├── go.mod
│   ├── go.sum
│   ├── internal
│   │   ├── binres
│   │   │   ├── arsc.go
│   │   │   ├── binres.go
│   │   │   ├── binres_string.go
│   │   │   ├── binres_test.go
│   │   │   ├── genarsc.go
│   │   │   ├── node.go
│   │   │   ├── pool.go
│   │   │   ├── sdk.go
│   │   │   ├── table.go
│   │   │   └── testdata
│   │   │       ├── bootstrap.arsc
│   │   │       ├── bootstrap.bin
│   │   │       ├── bootstrap-res
│   │   │       │   └── mipmap-xxxhdpi
│   │   │       │       └── icon.png
│   │   │       ├── bootstrap.xml
│   │   │       └── gen.sh
│   │   ├── importers
│   │   │   ├── ast.go
│   │   │   ├── ast_test.go
│   │   │   ├── java
│   │   │   │   ├── java.go
│   │   │   │   └── java_test.go
│   │   │   └── objc
│   │   │       ├── objc.go
│   │   │       └── objc_test.go
│   │   └── mobileinit
│   │       ├── ctx_android.go
│   │       ├── mobileinit_android.go
│   │       ├── mobileinit.go
│   │       └── mobileinit_ios.go
│   ├── LICENSE
│   ├── PATENTS
│   ├── README.md
│   └── testdata
│       ├── gophercolor.png
│       ├── gopherswim.png
│       ├── testpattern.png
│       └── testpattern-window.png
├── net
│   ├── AUTHORS
│   ├── bpf
│   │   ├── asm.go
│   │   ├── constants.go
│   │   ├── doc.go
│   │   ├── instructions.go
│   │   ├── instructions_test.go
│   │   ├── setter.go
│   │   ├── testdata
│   │   │   ├── all_instructions.bpf
│   │   │   └── all_instructions.txt
│   │   ├── vm_aluop_test.go
│   │   ├── vm_bpf_test.go
│   │   ├── vm_extension_test.go
│   │   ├── vm.go
│   │   ├── vm_instructions.go
│   │   ├── vm_jump_test.go
│   │   ├── vm_load_test.go
│   │   ├── vm_ret_test.go
│   │   ├── vm_scratch_test.go
│   │   └── vm_test.go
│   ├── codereview.cfg
│   ├── context
│   │   ├── context.go
│   │   ├── context_test.go
│   │   ├── ctxhttp
│   │   │   ├── ctxhttp.go
│   │   │   └── ctxhttp_test.go
│   │   ├── go17.go
│   │   ├── go19.go
│   │   ├── pre_go17.go
│   │   ├── pre_go19.go
│   │   └── withtimeout_test.go
│   ├── CONTRIBUTING.md
│   ├── CONTRIBUTORS
│   ├── dict
│   │   └── dict.go
│   ├── dns
│   │   └── dnsmessage
│   │       ├── example_test.go
│   │       ├── message.go
│   │       └── message_test.go
│   ├── go.mod
│   ├── go.sum
│   ├── html
│   │   ├── atom
│   │   │   ├── atom.go
│   │   │   ├── atom_test.go
│   │   │   ├── gen.go
│   │   │   ├── table.go
│   │   │   └── table_test.go
│   │   ├── charset
│   │   │   ├── charset.go
│   │   │   ├── charset_test.go
│   │   │   └── testdata
│   │   │       ├── HTTP-charset.html
│   │   │       ├── HTTP-vs-meta-charset.html
│   │   │       ├── HTTP-vs-meta-content.html
│   │   │       ├── HTTP-vs-UTF-8-BOM.html
│   │   │       ├── meta-charset-attribute.html
│   │   │       ├── meta-content-attribute.html
│   │   │       ├── No-encoding-declaration.html
│   │   │       ├── README
│   │   │       ├── UTF-16BE-BOM.html
│   │   │       ├── UTF-16LE-BOM.html
│   │   │       ├── UTF-8-BOM-vs-meta-charset.html
│   │   │       └── UTF-8-BOM-vs-meta-content.html
│   │   ├── const.go
│   │   ├── doc.go
│   │   ├── doctype.go
│   │   ├── entity.go
│   │   ├── entity_test.go
│   │   ├── escape.go
│   │   ├── escape_test.go
│   │   ├── example_test.go
│   │   ├── foreign.go
│   │   ├── node.go
│   │   ├── node_test.go
│   │   ├── parse.go
│   │   ├── parse_test.go
│   │   ├── render.go
│   │   ├── render_test.go
│   │   ├── testdata
│   │   │   ├── go
│   │   │   │   ├── issue_30600_parse_panics_in_cell_mode.dat
│   │   │   │   ├── issue_30961_error_nested_unknown_tag_types.dat
│   │   │   │   ├── select.dat
│   │   │   │   └── template.dat
│   │   │   ├── go1.html
│   │   │   └── webkit
│   │   │       ├── adoption01.dat
│   │   │       ├── adoption02.dat
│   │   │       ├── blocks.dat
│   │   │       ├── comments01.dat
│   │   │       ├── doctype01.dat
│   │   │       ├── domjs-unsafe.dat
│   │   │       ├── entities01.dat
│   │   │       ├── entities02.dat
│   │   │       ├── html5test-com.dat
│   │   │       ├── inbody01.dat
│   │   │       ├── isindex.dat
│   │   │       ├── math.dat
│   │   │       ├── namespace-sensitivity.dat
│   │   │       ├── pending-spec-changes.dat
│   │   │       ├── pending-spec-changes-plain-text-unsafe.dat
│   │   │       ├── plain-text-unsafe.dat
│   │   │       ├── README
│   │   │       ├── ruby.dat
│   │   │       ├── scriptdata01.dat
│   │   │       ├── scripted
│   │   │       │   ├── adoption01.dat
│   │   │       │   ├── ark.dat
│   │   │       │   └── webkit01.dat
│   │   │       ├── tables01.dat
│   │   │       ├── template.dat
│   │   │       ├── tests10.dat
│   │   │       ├── tests11.dat
│   │   │       ├── tests12.dat
│   │   │       ├── tests14.dat
│   │   │       ├── tests15.dat
│   │   │       ├── tests16.dat
│   │   │       ├── tests17.dat
│   │   │       ├── tests18.dat
│   │   │       ├── tests19.dat
│   │   │       ├── tests1.dat
│   │   │       ├── tests20.dat
│   │   │       ├── tests21.dat
│   │   │       ├── tests22.dat
│   │   │       ├── tests23.dat
│   │   │       ├── tests24.dat
│   │   │       ├── tests25.dat
│   │   │       ├── tests26.dat
│   │   │       ├── tests2.dat
│   │   │       ├── tests3.dat
│   │   │       ├── tests4.dat
│   │   │       ├── tests5.dat
│   │   │       ├── tests6.dat
│   │   │       ├── tests7.dat
│   │   │       ├── tests8.dat
│   │   │       ├── tests9.dat
│   │   │       ├── tests_innerHTML_1.dat
│   │   │       ├── tricky01.dat
│   │   │       ├── webkit01.dat
│   │   │       └── webkit02.dat
│   │   ├── token.go
│   │   └── token_test.go
│   ├── http
│   │   ├── httpguts
│   │   │   ├── guts.go
│   │   │   ├── httplex.go
│   │   │   └── httplex_test.go
│   │   └── httpproxy
│   │       ├── export_test.go
│   │       ├── go19_test.go
│   │       ├── proxy.go
│   │       └── proxy_test.go
│   ├── http2
│   │   ├── ciphers.go
│   │   ├── ciphers_test.go
│   │   ├── client_conn_pool.go
│   │   ├── databuffer.go
│   │   ├── databuffer_test.go
│   │   ├── Dockerfile
│   │   ├── errors.go
│   │   ├── errors_test.go
│   │   ├── flow.go
│   │   ├── flow_test.go
│   │   ├── frame.go
│   │   ├── frame_test.go
│   │   ├── go111.go
│   │   ├── gotrack.go
│   │   ├── gotrack_test.go
│   │   ├── h2c
│   │   │   ├── h2c.go
│   │   │   └── h2c_test.go
│   │   ├── h2demo
│   │   │   ├── deployment-prod.yaml
│   │   │   ├── Dockerfile
│   │   │   ├── go.mod
│   │   │   ├── go.sum
│   │   │   ├── h2demo.go
│   │   │   ├── Makefile
│   │   │   ├── README
│   │   │   ├── rootCA.key
│   │   │   ├── rootCA.pem
│   │   │   ├── rootCA.srl
│   │   │   ├── server.crt
│   │   │   ├── server.key
│   │   │   ├── service.yaml
│   │   │   └── tmpl.go
│   │   ├── h2i
│   │   │   ├── h2i.go
│   │   │   └── README.md
│   │   ├── headermap.go
│   │   ├── hpack
│   │   │   ├── encode.go
│   │   │   ├── encode_test.go
│   │   │   ├── hpack.go
│   │   │   ├── hpack_test.go
│   │   │   ├── huffman.go
│   │   │   ├── tables.go
│   │   │   └── tables_test.go
│   │   ├── http2.go
│   │   ├── http2_test.go
│   │   ├── Makefile
│   │   ├── not_go111.go
│   │   ├── pipe.go
│   │   ├── pipe_test.go
│   │   ├── README
│   │   ├── server.go
│   │   ├── server_push_test.go
│   │   ├── server_test.go
│   │   ├── testdata
│   │   │   └── draft-ietf-httpbis-http2.xml
│   │   ├── transport.go
│   │   ├── transport_test.go
│   │   ├── write.go
│   │   ├── writesched.go
│   │   ├── writesched_priority.go
│   │   ├── writesched_priority_test.go
│   │   ├── writesched_random.go
│   │   ├── writesched_random_test.go
│   │   ├── writesched_test.go
│   │   └── z_spec_test.go
│   ├── icmp
│   │   ├── diag_test.go
│   │   ├── dstunreach.go
│   │   ├── echo.go
│   │   ├── endpoint.go
│   │   ├── example_test.go
│   │   ├── extension.go
│   │   ├── extension_test.go
│   │   ├── helper_posix.go
│   │   ├── interface.go
│   │   ├── ipv4.go
│   │   ├── ipv4_test.go
│   │   ├── ipv6.go
│   │   ├── listen_posix.go
│   │   ├── listen_stub.go
│   │   ├── messagebody.go
│   │   ├── message.go
│   │   ├── message_test.go
│   │   ├── mpls.go
│   │   ├── multipart.go
│   │   ├── multipart_test.go
│   │   ├── packettoobig.go
│   │   ├── paramprob.go
│   │   ├── sys_freebsd.go
│   │   └── timeexceeded.go
│   ├── idna
│   │   ├── example_test.go
│   │   ├── idna10.0.0.go
│   │   ├── idna9.0.0.go
│   │   ├── idna_test.go
│   │   ├── punycode.go
│   │   ├── punycode_test.go
│   │   ├── tables10.0.0.go
│   │   ├── tables11.0.0.go
│   │   ├── tables12.00.go
│   │   ├── tables9.0.0.go
│   │   ├── trie.go
│   │   └── trieval.go
│   ├── internal
│   │   ├── iana
│   │   │   ├── const.go
│   │   │   └── gen.go
│   │   ├── socket
│   │   │   ├── cmsghdr_bsd.go
│   │   │   ├── cmsghdr.go
│   │   │   ├── cmsghdr_linux_32bit.go
│   │   │   ├── cmsghdr_linux_64bit.go
│   │   │   ├── cmsghdr_solaris_64bit.go
│   │   │   ├── cmsghdr_stub.go
│   │   │   ├── defs_aix.go
│   │   │   ├── defs_darwin.go
│   │   │   ├── defs_dragonfly.go
│   │   │   ├── defs_freebsd.go
│   │   │   ├── defs_linux.go
│   │   │   ├── defs_netbsd.go
│   │   │   ├── defs_openbsd.go
│   │   │   ├── defs_solaris.go
│   │   │   ├── empty.s
│   │   │   ├── error_unix.go
│   │   │   ├── error_windows.go
│   │   │   ├── iovec_32bit.go
│   │   │   ├── iovec_64bit.go
│   │   │   ├── iovec_solaris_64bit.go
│   │   │   ├── iovec_stub.go
│   │   │   ├── mmsghdr_stub.go
│   │   │   ├── mmsghdr_unix.go
│   │   │   ├── msghdr_bsd.go
│   │   │   ├── msghdr_bsdvar.go
│   │   │   ├── msghdr_linux_32bit.go
│   │   │   ├── msghdr_linux_64bit.go
│   │   │   ├── msghdr_linux.go
│   │   │   ├── msghdr_openbsd.go
│   │   │   ├── msghdr_solaris_64bit.go
│   │   │   ├── msghdr_stub.go
│   │   │   ├── norace.go
│   │   │   ├── race.go
│   │   │   ├── rawconn.go
│   │   │   ├── rawconn_mmsg.go
│   │   │   ├── rawconn_msg.go
│   │   │   ├── rawconn_nommsg.go
│   │   │   ├── rawconn_nomsg.go
│   │   │   ├── socket.go
│   │   │   ├── socket_test.go
│   │   │   ├── sys_bsd.go
│   │   │   ├── sys_bsdvar.go
│   │   │   ├── sys_const_unix.go
│   │   │   ├── sys_darwin.go
│   │   │   ├── sys_dragonfly.go
│   │   │   ├── sys.go
│   │   │   ├── sys_go1_11_darwin.go
│   │   │   ├── sys_linkname.go
│   │   │   ├── sys_linux_386.go
│   │   │   ├── sys_linux_386.s
│   │   │   ├── sys_linux_amd64.go
│   │   │   ├── sys_linux_arm64.go
│   │   │   ├── sys_linux_arm.go
│   │   │   ├── sys_linux.go
│   │   │   ├── sys_linux_mips64.go
│   │   │   ├── sys_linux_mips64le.go
│   │   │   ├── sys_linux_mips.go
│   │   │   ├── sys_linux_mipsle.go
│   │   │   ├── sys_linux_ppc64.go
│   │   │   ├── sys_linux_ppc64le.go
│   │   │   ├── sys_linux_riscv64.go
│   │   │   ├── sys_linux_s390x.go
│   │   │   ├── sys_linux_s390x.s
│   │   │   ├── sys_netbsd.go
│   │   │   ├── sys_posix.go
│   │   │   ├── sys_solaris_amd64.s
│   │   │   ├── sys_solaris.go
│   │   │   ├── sys_stub.go
│   │   │   ├── sys_unix.go
│   │   │   ├── sys_windows.go
│   │   │   ├── zsys_aix_ppc64.go
│   │   │   ├── zsys_darwin_386.go
│   │   │   ├── zsys_darwin_amd64.go
│   │   │   ├── zsys_darwin_arm64.go
│   │   │   ├── zsys_darwin_arm.go
│   │   │   ├── zsys_dragonfly_amd64.go
│   │   │   ├── zsys_freebsd_386.go
│   │   │   ├── zsys_freebsd_amd64.go
│   │   │   ├── zsys_freebsd_arm64.go
│   │   │   ├── zsys_freebsd_arm.go
│   │   │   ├── zsys_linux_386.go
│   │   │   ├── zsys_linux_amd64.go
│   │   │   ├── zsys_linux_arm64.go
│   │   │   ├── zsys_linux_arm.go
│   │   │   ├── zsys_linux_mips64.go
│   │   │   ├── zsys_linux_mips64le.go
│   │   │   ├── zsys_linux_mips.go
│   │   │   ├── zsys_linux_mipsle.go
│   │   │   ├── zsys_linux_ppc64.go
│   │   │   ├── zsys_linux_ppc64le.go
│   │   │   ├── zsys_linux_riscv64.go
│   │   │   ├── zsys_linux_s390x.go
│   │   │   ├── zsys_netbsd_386.go
│   │   │   ├── zsys_netbsd_amd64.go
│   │   │   ├── zsys_netbsd_arm64.go
│   │   │   ├── zsys_netbsd_arm.go
│   │   │   ├── zsys_openbsd_386.go
│   │   │   ├── zsys_openbsd_amd64.go
│   │   │   ├── zsys_openbsd_arm64.go
│   │   │   ├── zsys_openbsd_arm.go
│   │   │   └── zsys_solaris_amd64.go
│   │   ├── socks
│   │   │   ├── client.go
│   │   │   ├── dial_test.go
│   │   │   └── socks.go
│   │   ├── sockstest
│   │   │   ├── server.go
│   │   │   └── server_test.go
│   │   └── timeseries
│   │       ├── timeseries.go
│   │       └── timeseries_test.go
│   ├── ipv4
│   │   ├── batch.go
│   │   ├── bpf_test.go
│   │   ├── control_bsd.go
│   │   ├── control.go
│   │   ├── control_pktinfo.go
│   │   ├── control_stub.go
│   │   ├── control_test.go
│   │   ├── control_unix.go
│   │   ├── control_windows.go
│   │   ├── defs_aix.go
│   │   ├── defs_darwin.go
│   │   ├── defs_dragonfly.go
│   │   ├── defs_freebsd.go
│   │   ├── defs_linux.go
│   │   ├── defs_netbsd.go
│   │   ├── defs_openbsd.go
│   │   ├── defs_solaris.go
│   │   ├── dgramopt.go
│   │   ├── doc.go
│   │   ├── endpoint.go
│   │   ├── example_test.go
│   │   ├── genericopt.go
│   │   ├── gen.go
│   │   ├── header.go
│   │   ├── header_test.go
│   │   ├── helper.go
│   │   ├── helper_posix_test.go
│   │   ├── helper_stub_test.go
│   │   ├── iana.go
│   │   ├── icmp.go
│   │   ├── icmp_linux.go
│   │   ├── icmp_stub.go
│   │   ├── icmp_test.go
│   │   ├── multicastlistener_test.go
│   │   ├── multicastsockopt_test.go
│   │   ├── multicast_test.go
│   │   ├── packet.go
│   │   ├── payload_cmsg.go
│   │   ├── payload.go
│   │   ├── payload_nocmsg.go
│   │   ├── readwrite_test.go
│   │   ├── sockopt.go
│   │   ├── sockopt_posix.go
│   │   ├── sockopt_stub.go
│   │   ├── sys_aix.go
│   │   ├── sys_asmreq.go
│   │   ├── sys_asmreqn.go
│   │   ├── sys_asmreqn_stub.go
│   │   ├── sys_asmreq_stub.go
│   │   ├── sys_bpf.go
│   │   ├── sys_bpf_stub.go
│   │   ├── sys_bsd.go
│   │   ├── sys_darwin.go
│   │   ├── sys_dragonfly.go
│   │   ├── sys_freebsd.go
│   │   ├── sys_linux.go
│   │   ├── sys_solaris.go
│   │   ├── sys_ssmreq.go
│   │   ├── sys_ssmreq_stub.go
│   │   ├── sys_stub.go
│   │   ├── sys_windows.go
│   │   ├── unicastsockopt_test.go
│   │   ├── unicast_test.go
│   │   ├── zsys_aix_ppc64.go
│   │   ├── zsys_darwin.go
│   │   ├── zsys_dragonfly.go
│   │   ├── zsys_freebsd_386.go
│   │   ├── zsys_freebsd_amd64.go
│   │   ├── zsys_freebsd_arm64.go
│   │   ├── zsys_freebsd_arm.go
│   │   ├── zsys_linux_386.go
│   │   ├── zsys_linux_amd64.go
│   │   ├── zsys_linux_arm64.go
│   │   ├── zsys_linux_arm.go
│   │   ├── zsys_linux_mips64.go
│   │   ├── zsys_linux_mips64le.go
│   │   ├── zsys_linux_mips.go
│   │   ├── zsys_linux_mipsle.go
│   │   ├── zsys_linux_ppc64.go
│   │   ├── zsys_linux_ppc64le.go
│   │   ├── zsys_linux_ppc.go
│   │   ├── zsys_linux_riscv64.go
│   │   ├── zsys_linux_s390x.go
│   │   ├── zsys_netbsd.go
│   │   ├── zsys_openbsd.go
│   │   └── zsys_solaris.go
│   ├── ipv6
│   │   ├── batch.go
│   │   ├── bpf_test.go
│   │   ├── control.go
│   │   ├── control_rfc2292_unix.go
│   │   ├── control_rfc3542_unix.go
│   │   ├── control_stub.go
│   │   ├── control_test.go
│   │   ├── control_unix.go
│   │   ├── control_windows.go
│   │   ├── defs_aix.go
│   │   ├── defs_darwin.go
│   │   ├── defs_dragonfly.go
│   │   ├── defs_freebsd.go
│   │   ├── defs_linux.go
│   │   ├── defs_netbsd.go
│   │   ├── defs_openbsd.go
│   │   ├── defs_solaris.go
│   │   ├── dgramopt.go
│   │   ├── doc.go
│   │   ├── endpoint.go
│   │   ├── example_test.go
│   │   ├── genericopt.go
│   │   ├── gen.go
│   │   ├── header.go
│   │   ├── header_test.go
│   │   ├── helper.go
│   │   ├── helper_posix_test.go
│   │   ├── helper_stub_test.go
│   │   ├── helper_unix_test.go
│   │   ├── helper_windows_test.go
│   │   ├── iana.go
│   │   ├── icmp_bsd.go
│   │   ├── icmp.go
│   │   ├── icmp_linux.go
│   │   ├── icmp_solaris.go
│   │   ├── icmp_stub.go
│   │   ├── icmp_test.go
│   │   ├── icmp_windows.go
│   │   ├── mocktransponder_test.go
│   │   ├── multicastlistener_test.go
│   │   ├── multicastsockopt_test.go
│   │   ├── multicast_test.go
│   │   ├── payload_cmsg.go
│   │   ├── payload.go
│   │   ├── payload_nocmsg.go
│   │   ├── readwrite_test.go
│   │   ├── sockopt.go
│   │   ├── sockopt_posix.go
│   │   ├── sockopt_stub.go
│   │   ├── sockopt_test.go
│   │   ├── sys_aix.go
│   │   ├── sys_asmreq.go
│   │   ├── sys_asmreq_stub.go
│   │   ├── sys_bpf.go
│   │   ├── sys_bpf_stub.go
│   │   ├── sys_bsd.go
│   │   ├── sys_darwin.go
│   │   ├── sys_freebsd.go
│   │   ├── sys_linux.go
│   │   ├── sys_solaris.go
│   │   ├── sys_ssmreq.go
│   │   ├── sys_ssmreq_stub.go
│   │   ├── sys_stub.go
│   │   ├── sys_windows.go
│   │   ├── unicastsockopt_test.go
│   │   ├── unicast_test.go
│   │   ├── zsys_aix_ppc64.go
│   │   ├── zsys_darwin.go
│   │   ├── zsys_dragonfly.go
│   │   ├── zsys_freebsd_386.go
│   │   ├── zsys_freebsd_amd64.go
│   │   ├── zsys_freebsd_arm64.go
│   │   ├── zsys_freebsd_arm.go
│   │   ├── zsys_linux_386.go
│   │   ├── zsys_linux_amd64.go
│   │   ├── zsys_linux_arm64.go
│   │   ├── zsys_linux_arm.go
│   │   ├── zsys_linux_mips64.go
│   │   ├── zsys_linux_mips64le.go
│   │   ├── zsys_linux_mips.go
│   │   ├── zsys_linux_mipsle.go
│   │   ├── zsys_linux_ppc64.go
│   │   ├── zsys_linux_ppc64le.go
│   │   ├── zsys_linux_ppc.go
│   │   ├── zsys_linux_riscv64.go
│   │   ├── zsys_linux_s390x.go
│   │   ├── zsys_netbsd.go
│   │   ├── zsys_openbsd.go
│   │   └── zsys_solaris.go
│   ├── LICENSE
│   ├── lif
│   │   ├── address.go
│   │   ├── address_test.go
│   │   ├── binary.go
│   │   ├── defs_solaris.go
│   │   ├── lif.go
│   │   ├── link.go
│   │   ├── link_test.go
│   │   ├── syscall.go
│   │   ├── sys.go
│   │   ├── sys_solaris_amd64.s
│   │   └── zsys_solaris_amd64.go
│   ├── nettest
│   │   ├── conntest.go
│   │   ├── conntest_test.go
│   │   ├── nettest.go
│   │   ├── nettest_stub.go
│   │   ├── nettest_unix.go
│   │   └── nettest_windows.go
│   ├── netutil
│   │   ├── helper_stub_test.go
│   │   ├── helper_unix_test.go
│   │   ├── helper_windows_test.go
│   │   ├── listen.go
│   │   └── listen_test.go
│   ├── PATENTS
│   ├── proxy
│   │   ├── dial.go
│   │   ├── dial_test.go
│   │   ├── direct.go
│   │   ├── per_host.go
│   │   ├── per_host_test.go
│   │   ├── proxy.go
│   │   ├── proxy_test.go
│   │   └── socks5.go
│   ├── publicsuffix
│   │   ├── example_test.go
│   │   ├── gen.go
│   │   ├── list.go
│   │   ├── list_test.go
│   │   ├── table.go
│   │   └── table_test.go
│   ├── README.md
│   ├── route
│   │   ├── address_darwin_test.go
│   │   ├── address.go
│   │   ├── address_test.go
│   │   ├── binary.go
│   │   ├── defs_darwin.go
│   │   ├── defs_dragonfly.go
│   │   ├── defs_freebsd.go
│   │   ├── defs_netbsd.go
│   │   ├── defs_openbsd.go
│   │   ├── empty.s
│   │   ├── interface_announce.go
│   │   ├── interface_classic.go
│   │   ├── interface_freebsd.go
│   │   ├── interface.go
│   │   ├── interface_multicast.go
│   │   ├── interface_openbsd.go
│   │   ├── message_darwin_test.go
│   │   ├── message_freebsd_test.go
│   │   ├── message.go
│   │   ├── message_test.go
│   │   ├── route_classic.go
│   │   ├── route.go
│   │   ├── route_openbsd.go
│   │   ├── route_test.go
│   │   ├── syscall.go
│   │   ├── syscall_go1_11_darwin.go
│   │   ├── syscall_go1_12_darwin.go
│   │   ├── sys_darwin.go
│   │   ├── sys_dragonfly.go
│   │   ├── sys_freebsd.go
│   │   ├── sys.go
│   │   ├── sys_netbsd.go
│   │   ├── sys_openbsd.go
│   │   ├── zsys_darwin.go
│   │   ├── zsys_dragonfly.go
│   │   ├── zsys_freebsd_386.go
│   │   ├── zsys_freebsd_amd64.go
│   │   ├── zsys_freebsd_arm64.go
│   │   ├── zsys_freebsd_arm.go
│   │   ├── zsys_netbsd.go
│   │   └── zsys_openbsd.go
│   ├── trace
│   │   ├── events.go
│   │   ├── histogram.go
│   │   ├── histogram_test.go
│   │   ├── trace.go
│   │   └── trace_test.go
│   ├── webdav
│   │   ├── file.go
│   │   ├── file_test.go
│   │   ├── if.go
│   │   ├── if_test.go
│   │   ├── internal
│   │   │   └── xml
│   │   │       ├── atom_test.go
│   │   │       ├── example_test.go
│   │   │       ├── marshal.go
│   │   │       ├── marshal_test.go
│   │   │       ├── read.go
│   │   │       ├── README
│   │   │       ├── read_test.go
│   │   │       ├── typeinfo.go
│   │   │       ├── xml.go
│   │   │       └── xml_test.go
│   │   ├── litmus_test_server.go
│   │   ├── lock.go
│   │   ├── lock_test.go
│   │   ├── prop.go
│   │   ├── prop_test.go
│   │   ├── webdav.go
│   │   ├── webdav_test.go
│   │   ├── xml.go
│   │   └── xml_test.go
│   ├── websocket
│   │   ├── client.go
│   │   ├── dial.go
│   │   ├── dial_test.go
│   │   ├── exampledial_test.go
│   │   ├── examplehandler_test.go
│   │   ├── hybi.go
│   │   ├── hybi_test.go
│   │   ├── server.go
│   │   ├── websocket.go
│   │   └── websocket_test.go
│   └── xsrftoken
│       ├── xsrf.go
│       └── xsrf_test.go
├── sys
│   ├── AUTHORS
│   ├── codereview.cfg
│   ├── CONTRIBUTING.md
│   ├── CONTRIBUTORS
│   ├── cpu
│   │   ├── asm_aix_ppc64.s
│   │   ├── byteorder.go
│   │   ├── cpu_aix_ppc64.go
│   │   ├── cpu_arm.go
│   │   ├── cpu_gccgo.c
│   │   ├── cpu_gccgo.go
│   │   ├── cpu_gccgo_s390x.go
│   │   ├── cpu_gc_s390x.go
│   │   ├── cpu_gc_x86.go
│   │   ├── cpu.go
│   │   ├── cpu_linux_arm64.go
│   │   ├── cpu_linux_arm.go
│   │   ├── cpu_linux.go
│   │   ├── cpu_linux_ppc64x.go
│   │   ├── cpu_linux_s390x.go
│   │   ├── cpu_mips64x.go
│   │   ├── cpu_mipsx.go
│   │   ├── cpu_other_arm64.go
│   │   ├── cpu_s390x.s
│   │   ├── cpu_test.go
│   │   ├── cpu_wasm.go
│   │   ├── cpu_x86.go
│   │   ├── cpu_x86.s
│   │   └── syscall_aix_ppc64_gc.go
│   ├── go.mod
│   ├── LICENSE
│   ├── PATENTS
│   ├── plan9
│   │   ├── asm_plan9_386.s
│   │   ├── asm_plan9_amd64.s
│   │   ├── asm_plan9_arm.s
│   │   ├── asm.s
│   │   ├── const_plan9.go
│   │   ├── dir_plan9.go
│   │   ├── env_plan9.go
│   │   ├── errors_plan9.go
│   │   ├── mkall.sh
│   │   ├── mkerrors.sh
│   │   ├── mksyscall.go
│   │   ├── mksysnum_plan9.sh
│   │   ├── pwd_go15_plan9.go
│   │   ├── pwd_plan9.go
│   │   ├── race0.go
│   │   ├── race.go
│   │   ├── str.go
│   │   ├── syscall.go
│   │   ├── syscall_plan9.go
│   │   ├── syscall_test.go
│   │   ├── zsyscall_plan9_386.go
│   │   ├── zsyscall_plan9_amd64.go
│   │   ├── zsyscall_plan9_arm.go
│   │   └── zsysnum_plan9.go
│   ├── README.md
│   ├── unix
│   │   ├── affinity_linux.go
│   │   ├── aliases.go
│   │   ├── asm_aix_ppc64.s
│   │   ├── asm_darwin_386.s
│   │   ├── asm_darwin_amd64.s
│   │   ├── asm_darwin_arm64.s
│   │   ├── asm_darwin_arm.s
│   │   ├── asm_dragonfly_amd64.s
│   │   ├── asm_freebsd_386.s
│   │   ├── asm_freebsd_amd64.s
│   │   ├── asm_freebsd_arm64.s
│   │   ├── asm_freebsd_arm.s
│   │   ├── asm_linux_386.s
│   │   ├── asm_linux_amd64.s
│   │   ├── asm_linux_arm64.s
│   │   ├── asm_linux_arm.s
│   │   ├── asm_linux_mips64x.s
│   │   ├── asm_linux_mipsx.s
│   │   ├── asm_linux_ppc64x.s
│   │   ├── asm_linux_riscv64.s
│   │   ├── asm_linux_s390x.s
│   │   ├── asm_netbsd_386.s
│   │   ├── asm_netbsd_amd64.s
│   │   ├── asm_netbsd_arm64.s
│   │   ├── asm_netbsd_arm.s
│   │   ├── asm_openbsd_386.s
│   │   ├── asm_openbsd_amd64.s
│   │   ├── asm_openbsd_arm64.s
│   │   ├── asm_openbsd_arm.s
│   │   ├── asm_solaris_amd64.s
│   │   ├── bluetooth_linux.go
│   │   ├── cap_freebsd.go
│   │   ├── constants.go
│   │   ├── creds_test.go
│   │   ├── darwin_test.go
│   │   ├── dev_aix_ppc64.go
│   │   ├── dev_aix_ppc.go
│   │   ├── dev_darwin.go
│   │   ├── dev_dragonfly.go
│   │   ├── dev_freebsd.go
│   │   ├── dev_linux.go
│   │   ├── dev_linux_test.go
│   │   ├── dev_netbsd.go
│   │   ├── dev_openbsd.go
│   │   ├── dirent.go
│   │   ├── dirent_test.go
│   │   ├── endian_big.go
│   │   ├── endian_little.go
│   │   ├── env_unix.go
│   │   ├── errors_freebsd_386.go
│   │   ├── errors_freebsd_amd64.go
│   │   ├── errors_freebsd_arm.go
│   │   ├── example_exec_test.go
│   │   ├── example_flock_test.go
│   │   ├── export_test.go
│   │   ├── fcntl_darwin.go
│   │   ├── fcntl.go
│   │   ├── fcntl_linux_32bit.go
│   │   ├── fdset.go
│   │   ├── fdset_test.go
│   │   ├── gccgo_c.c
│   │   ├── gccgo.go
│   │   ├── gccgo_linux_amd64.go
│   │   ├── getdirentries_test.go
│   │   ├── ioctl.go
│   │   ├── linux
│   │   │   ├── Dockerfile
│   │   │   ├── mkall.go
│   │   │   ├── mksysnum.go
│   │   │   └── types.go
│   │   ├── mkall.sh
│   │   ├── mkasm_darwin.go
│   │   ├── mkerrors.sh
│   │   ├── mkpost.go
│   │   ├── mksyscall_aix_ppc64.go
│   │   ├── mksyscall_aix_ppc.go
│   │   ├── mksyscall.go
│   │   ├── mksyscall_solaris.go
│   │   ├── mksysctl_openbsd.go
│   │   ├── mksysnum.go
│   │   ├── mmap_unix_test.go
│   │   ├── openbsd_test.go
│   │   ├── pagesize_unix.go
│   │   ├── pledge_openbsd.go
│   │   ├── race0.go
│   │   ├── race.go
│   │   ├── readdirent_getdents.go
│   │   ├── readdirent_getdirentries.go
│   │   ├── README.md
│   │   ├── sendfile_test.go
│   │   ├── sockcmsg_dragonfly.go
│   │   ├── sockcmsg_linux.go
│   │   ├── sockcmsg_unix.go
│   │   ├── sockcmsg_unix_other.go
│   │   ├── str.go
│   │   ├── syscall_aix.go
│   │   ├── syscall_aix_ppc64.go
│   │   ├── syscall_aix_ppc.go
│   │   ├── syscall_aix_test.go
│   │   ├── syscall_bsd.go
│   │   ├── syscall_bsd_test.go
│   │   ├── syscall_darwin.1_12.go
│   │   ├── syscall_darwin.1_13.go
│   │   ├── syscall_darwin_386.1_11.go
│   │   ├── syscall_darwin_386.go
│   │   ├── syscall_darwin_amd64.1_11.go
│   │   ├── syscall_darwin_amd64.go
│   │   ├── syscall_darwin_arm.1_11.go
│   │   ├── syscall_darwin_arm64.1_11.go
│   │   ├── syscall_darwin_arm64.go
│   │   ├── syscall_darwin_arm.go
│   │   ├── syscall_darwin.go
│   │   ├── syscall_darwin_libSystem.go
│   │   ├── syscall_darwin_test.go
│   │   ├── syscall_dragonfly_amd64.go
│   │   ├── syscall_dragonfly.go
│   │   ├── syscall_freebsd_386.go
│   │   ├── syscall_freebsd_amd64.go
│   │   ├── syscall_freebsd_arm64.go
│   │   ├── syscall_freebsd_arm.go
│   │   ├── syscall_freebsd.go
│   │   ├── syscall_freebsd_test.go
│   │   ├── syscall.go
│   │   ├── syscall_internal_linux_test.go
│   │   ├── syscall_linux_386.go
│   │   ├── syscall_linux_amd64_gc.go
│   │   ├── syscall_linux_amd64.go
│   │   ├── syscall_linux_arm64.go
│   │   ├── syscall_linux_arm.go
│   │   ├── syscall_linux_gc_386.go
│   │   ├── syscall_linux_gccgo_386.go
│   │   ├── syscall_linux_gccgo_arm.go
│   │   ├── syscall_linux_gc.go
│   │   ├── syscall_linux.go
│   │   ├── syscall_linux_mips64x.go
│   │   ├── syscall_linux_mipsx.go
│   │   ├── syscall_linux_ppc64x.go
│   │   ├── syscall_linux_riscv64.go
│   │   ├── syscall_linux_s390x.go
│   │   ├── syscall_linux_sparc64.go
│   │   ├── syscall_linux_test.go
│   │   ├── syscall_netbsd_386.go
│   │   ├── syscall_netbsd_amd64.go
│   │   ├── syscall_netbsd_arm64.go
│   │   ├── syscall_netbsd_arm.go
│   │   ├── syscall_netbsd.go
│   │   ├── syscall_netbsd_test.go
│   │   ├── syscall_openbsd_386.go
│   │   ├── syscall_openbsd_amd64.go
│   │   ├── syscall_openbsd_arm64.go
│   │   ├── syscall_openbsd_arm.go
│   │   ├── syscall_openbsd.go
│   │   ├── syscall_openbsd_test.go
│   │   ├── syscall_solaris_amd64.go
│   │   ├── syscall_solaris.go
│   │   ├── syscall_solaris_test.go
│   │   ├── syscall_test.go
│   │   ├── syscall_unix_gc.go
│   │   ├── syscall_unix_gc_ppc64x.go
│   │   ├── syscall_unix.go
│   │   ├── syscall_unix_test.go
│   │   ├── timestruct.go
│   │   ├── timestruct_test.go
│   │   ├── types_aix.go
│   │   ├── types_darwin.go
│   │   ├── types_dragonfly.go
│   │   ├── types_freebsd.go
│   │   ├── types_netbsd.go
│   │   ├── types_openbsd.go
│   │   ├── types_solaris.go
│   │   ├── unveil_openbsd.go
│   │   ├── xattr_bsd.go
│   │   ├── xattr_test.go
│   │   ├── zerrors_aix_ppc64.go
│   │   ├── zerrors_aix_ppc.go
│   │   ├── zerrors_darwin_386.go
│   │   ├── zerrors_darwin_amd64.go
│   │   ├── zerrors_darwin_arm64.go
│   │   ├── zerrors_darwin_arm.go
│   │   ├── zerrors_dragonfly_amd64.go
│   │   ├── zerrors_freebsd_386.go
│   │   ├── zerrors_freebsd_amd64.go
│   │   ├── zerrors_freebsd_arm64.go
│   │   ├── zerrors_freebsd_arm.go
│   │   ├── zerrors_linux_386.go
│   │   ├── zerrors_linux_amd64.go
│   │   ├── zerrors_linux_arm64.go
│   │   ├── zerrors_linux_arm.go
│   │   ├── zerrors_linux_mips64.go
│   │   ├── zerrors_linux_mips64le.go
│   │   ├── zerrors_linux_mips.go
│   │   ├── zerrors_linux_mipsle.go
│   │   ├── zerrors_linux_ppc64.go
│   │   ├── zerrors_linux_ppc64le.go
│   │   ├── zerrors_linux_riscv64.go
│   │   ├── zerrors_linux_s390x.go
│   │   ├── zerrors_linux_sparc64.go
│   │   ├── zerrors_netbsd_386.go
│   │   ├── zerrors_netbsd_amd64.go
│   │   ├── zerrors_netbsd_arm64.go
│   │   ├── zerrors_netbsd_arm.go
│   │   ├── zerrors_openbsd_386.go
│   │   ├── zerrors_openbsd_amd64.go
│   │   ├── zerrors_openbsd_arm64.go
│   │   ├── zerrors_openbsd_arm.go
│   │   ├── zerrors_solaris_amd64.go
│   │   ├── zptrace386_linux.go
│   │   ├── zptracearm_linux.go
│   │   ├── zptracemipsle_linux.go
│   │   ├── zptracemips_linux.go
│   │   ├── zsyscall_aix_ppc64_gccgo.go
│   │   ├── zsyscall_aix_ppc64_gc.go
│   │   ├── zsyscall_aix_ppc64.go
│   │   ├── zsyscall_aix_ppc.go
│   │   ├── zsyscall_darwin_386.1_11.go
│   │   ├── zsyscall_darwin_386.1_13.go
│   │   ├── zsyscall_darwin_386.1_13.s
│   │   ├── zsyscall_darwin_386.go
│   │   ├── zsyscall_darwin_386.s
│   │   ├── zsyscall_darwin_amd64.1_11.go
│   │   ├── zsyscall_darwin_amd64.1_13.go
│   │   ├── zsyscall_darwin_amd64.1_13.s
│   │   ├── zsyscall_darwin_amd64.go
│   │   ├── zsyscall_darwin_amd64.s
│   │   ├── zsyscall_darwin_arm.1_11.go
│   │   ├── zsyscall_darwin_arm.1_13.go
│   │   ├── zsyscall_darwin_arm.1_13.s
│   │   ├── zsyscall_darwin_arm64.1_11.go
│   │   ├── zsyscall_darwin_arm64.1_13.go
│   │   ├── zsyscall_darwin_arm64.1_13.s
│   │   ├── zsyscall_darwin_arm64.go
│   │   ├── zsyscall_darwin_arm64.s
│   │   ├── zsyscall_darwin_arm.go
│   │   ├── zsyscall_darwin_arm.s
│   │   ├── zsyscall_dragonfly_amd64.go
│   │   ├── zsyscall_freebsd_386.go
│   │   ├── zsyscall_freebsd_amd64.go
│   │   ├── zsyscall_freebsd_arm64.go
│   │   ├── zsyscall_freebsd_arm.go
│   │   ├── zsyscall_linux_386.go
│   │   ├── zsyscall_linux_amd64.go
│   │   ├── zsyscall_linux_arm64.go
│   │   ├── zsyscall_linux_arm.go
│   │   ├── zsyscall_linux_mips64.go
│   │   ├── zsyscall_linux_mips64le.go
│   │   ├── zsyscall_linux_mips.go
│   │   ├── zsyscall_linux_mipsle.go
│   │   ├── zsyscall_linux_ppc64.go
│   │   ├── zsyscall_linux_ppc64le.go
│   │   ├── zsyscall_linux_riscv64.go
│   │   ├── zsyscall_linux_s390x.go
│   │   ├── zsyscall_linux_sparc64.go
│   │   ├── zsyscall_netbsd_386.go
│   │   ├── zsyscall_netbsd_amd64.go
│   │   ├── zsyscall_netbsd_arm64.go
│   │   ├── zsyscall_netbsd_arm.go
│   │   ├── zsyscall_openbsd_386.go
│   │   ├── zsyscall_openbsd_amd64.go
│   │   ├── zsyscall_openbsd_arm64.go
│   │   ├── zsyscall_openbsd_arm.go
│   │   ├── zsyscall_solaris_amd64.go
│   │   ├── zsysctl_openbsd_386.go
│   │   ├── zsysctl_openbsd_amd64.go
│   │   ├── zsysctl_openbsd_arm64.go
│   │   ├── zsysctl_openbsd_arm.go
│   │   ├── zsysnum_darwin_386.go
│   │   ├── zsysnum_darwin_amd64.go
│   │   ├── zsysnum_darwin_arm64.go
│   │   ├── zsysnum_darwin_arm.go
│   │   ├── zsysnum_dragonfly_amd64.go
│   │   ├── zsysnum_freebsd_386.go
│   │   ├── zsysnum_freebsd_amd64.go
│   │   ├── zsysnum_freebsd_arm64.go
│   │   ├── zsysnum_freebsd_arm.go
│   │   ├── zsysnum_linux_386.go
│   │   ├── zsysnum_linux_amd64.go
│   │   ├── zsysnum_linux_arm64.go
│   │   ├── zsysnum_linux_arm.go
│   │   ├── zsysnum_linux_mips64.go
│   │   ├── zsysnum_linux_mips64le.go
│   │   ├── zsysnum_linux_mips.go
│   │   ├── zsysnum_linux_mipsle.go
│   │   ├── zsysnum_linux_ppc64.go
│   │   ├── zsysnum_linux_ppc64le.go
│   │   ├── zsysnum_linux_riscv64.go
│   │   ├── zsysnum_linux_s390x.go
│   │   ├── zsysnum_linux_sparc64.go
│   │   ├── zsysnum_netbsd_386.go
│   │   ├── zsysnum_netbsd_amd64.go
│   │   ├── zsysnum_netbsd_arm64.go
│   │   ├── zsysnum_netbsd_arm.go
│   │   ├── zsysnum_openbsd_386.go
│   │   ├── zsysnum_openbsd_amd64.go
│   │   ├── zsysnum_openbsd_arm64.go
│   │   ├── zsysnum_openbsd_arm.go
│   │   ├── ztypes_aix_ppc64.go
│   │   ├── ztypes_aix_ppc.go
│   │   ├── ztypes_darwin_386.go
│   │   ├── ztypes_darwin_amd64.go
│   │   ├── ztypes_darwin_arm64.go
│   │   ├── ztypes_darwin_arm.go
│   │   ├── ztypes_dragonfly_amd64.go
│   │   ├── ztypes_freebsd_386.go
│   │   ├── ztypes_freebsd_amd64.go
│   │   ├── ztypes_freebsd_arm64.go
│   │   ├── ztypes_freebsd_arm.go
│   │   ├── ztypes_linux_386.go
│   │   ├── ztypes_linux_amd64.go
│   │   ├── ztypes_linux_arm64.go
│   │   ├── ztypes_linux_arm.go
│   │   ├── ztypes_linux_mips64.go
│   │   ├── ztypes_linux_mips64le.go
│   │   ├── ztypes_linux_mips.go
│   │   ├── ztypes_linux_mipsle.go
│   │   ├── ztypes_linux_ppc64.go
│   │   ├── ztypes_linux_ppc64le.go
│   │   ├── ztypes_linux_riscv64.go
│   │   ├── ztypes_linux_s390x.go
│   │   ├── ztypes_linux_sparc64.go
│   │   ├── ztypes_netbsd_386.go
│   │   ├── ztypes_netbsd_amd64.go
│   │   ├── ztypes_netbsd_arm64.go
│   │   ├── ztypes_netbsd_arm.go
│   │   ├── ztypes_openbsd_386.go
│   │   ├── ztypes_openbsd_amd64.go
│   │   ├── ztypes_openbsd_arm64.go
│   │   ├── ztypes_openbsd_arm.go
│   │   └── ztypes_solaris_amd64.go
│   └── windows
│       ├── aliases.go
│       ├── dll_windows.go
│       ├── empty.s
│       ├── env_windows.go
│       ├── eventlog.go
│       ├── exec_windows.go
│       ├── memory_windows.go
│       ├── mkerrors.bash
│       ├── mkknownfolderids.bash
│       ├── mksyscall.go
│       ├── mkwinsyscall
│       │   └── mkwinsyscall.go
│       ├── race0.go
│       ├── race.go
│       ├── registry
│       │   ├── export_test.go
│       │   ├── key.go
│       │   ├── mksyscall.go
│       │   ├── registry_test.go
│       │   ├── syscall.go
│       │   ├── value.go
│       │   └── zsyscall_windows.go
│       ├── security_windows.go
│       ├── service.go
│       ├── str.go
│       ├── svc
│       │   ├── debug
│       │   │   ├── log.go
│       │   │   └── service.go
│       │   ├── event.go
│       │   ├── eventlog
│       │   │   ├── install.go
│       │   │   ├── log.go
│       │   │   └── log_test.go
│       │   ├── example
│       │   │   ├── beep.go
│       │   │   ├── install.go
│       │   │   ├── main.go
│       │   │   ├── manage.go
│       │   │   └── service.go
│       │   ├── go12.c
│       │   ├── go12.go
│       │   ├── go13.go
│       │   ├── mgr
│       │   │   ├── config.go
│       │   │   ├── mgr.go
│       │   │   ├── mgr_test.go
│       │   │   ├── recovery.go
│       │   │   └── service.go
│       │   ├── security.go
│       │   ├── service.go
│       │   ├── svc_test.go
│       │   ├── sys_386.s
│       │   ├── sys_amd64.s
│       │   └── sys_arm.s
│       ├── syscall.go
│       ├── syscall_test.go
│       ├── syscall_windows.go
│       ├── syscall_windows_test.go
│       ├── types_windows_386.go
│       ├── types_windows_amd64.go
│       ├── types_windows_arm.go
│       ├── types_windows.go
│       ├── zerrors_windows.go
│       ├── zknownfolderids_windows.go
│       └── zsyscall_windows.go
├── talks
│   ├── app.yaml
│   ├── AUTHORS
│   ├── codereview.cfg
│   ├── content
│   │   ├── 2009
│   │   │   └── go_talk-20091030.pdf
│   │   ├── 2010
│   │   │   ├── ExpressivenessOfGo-2010.pdf
│   │   │   ├── gofrontend-gcc-summit-2010.pdf
│   │   │   ├── go_talk-20100112.html
│   │   │   ├── go_talk-20100121.html
│   │   │   ├── go_talk-20100323.html
│   │   │   ├── io
│   │   │   │   ├── balance.go
│   │   │   │   ├── decrypt.go
│   │   │   │   ├── encrypt.go
│   │   │   │   ├── eval1.go
│   │   │   │   ├── eval2.go
│   │   │   │   └── talk.pdf
│   │   │   └── support
│   │   │       ├── bumper480x270.png
│   │   │       ├── bumper640x360.png
│   │   │       ├── go-logo-white.png
│   │   │       ├── java-typing.png
│   │   │       ├── slidy.css
│   │   │       └── slidy.js
│   │   ├── 2011
│   │   │   ├── lex
│   │   │   │   ├── lex1.oldgo
│   │   │   │   ├── r59-lex.go
│   │   │   │   └── snippets
│   │   │   ├── lex.slide
│   │   │   ├── Real_World_Go.pdf
│   │   │   └── Writing_Web_Apps_in_Go.pdf
│   │   ├── 2012
│   │   │   ├── 10things
│   │   │   │   ├── 10.go
│   │   │   │   ├── 8.go
│   │   │   │   ├── 9b.go
│   │   │   │   ├── 9.go
│   │   │   │   └── gopher.jpg
│   │   │   ├── 10things.slide
│   │   │   ├── chat
│   │   │   │   ├── both
│   │   │   │   │   ├── chat.go
│   │   │   │   │   ├── html.go
│   │   │   │   │   └── markov.go
│   │   │   │   ├── diagrams.png
│   │   │   │   ├── gophers.jpg
│   │   │   │   ├── http
│   │   │   │   │   ├── chat.go
│   │   │   │   │   └── html.go
│   │   │   │   ├── http-noembed
│   │   │   │   │   ├── chat.go
│   │   │   │   │   └── html.go
│   │   │   │   ├── markov
│   │   │   │   │   ├── chat.go
│   │   │   │   │   ├── html.go
│   │   │   │   │   └── markov.go
│   │   │   │   ├── support
│   │   │   │   │   ├── chan.go
│   │   │   │   │   ├── defs.go
│   │   │   │   │   ├── echo.go
│   │   │   │   │   ├── echo-no-concurrency.go
│   │   │   │   │   ├── embed.go
│   │   │   │   │   ├── goroutines.go
│   │   │   │   │   ├── hello.go
│   │   │   │   │   ├── hello-net.go
│   │   │   │   │   ├── hello-web.go
│   │   │   │   │   ├── markov.txt
│   │   │   │   │   ├── select.go
│   │   │   │   │   ├── websocket.go
│   │   │   │   │   └── websocket.js
│   │   │   │   ├── tcp
│   │   │   │   │   └── chat.go
│   │   │   │   └── tcp-simple
│   │   │   │       └── chat.go
│   │   │   ├── chat.slide
│   │   │   ├── concurrency
│   │   │   │   ├── images
│   │   │   │   │   ├── gophereartrumpet.jpg
│   │   │   │   │   └── gophermegaphones.jpg
│   │   │   │   └── support
│   │   │   │       ├── boring.go
│   │   │   │       ├── changoboring.go
│   │   │   │       ├── chat.go
│   │   │   │       ├── daisy.go
│   │   │   │       ├── faninboring.go
│   │   │   │       ├── generator2boring.go
│   │   │   │       ├── generatorboring.go
│   │   │   │       ├── goboring.go
│   │   │   │       ├── google2.1.go
│   │   │   │       ├── google2.2.go
│   │   │   │       ├── google2.3.go
│   │   │   │       ├── google3.0.go
│   │   │   │       ├── google.go
│   │   │   │       ├── helpers.go
│   │   │   │       ├── lessboring.go
│   │   │   │       ├── mainboring.go
│   │   │   │       ├── quit.go
│   │   │   │       ├── rcvquit.go
│   │   │   │       ├── selectboring.go
│   │   │   │       ├── select.go
│   │   │   │       ├── sequenceboring.go
│   │   │   │       ├── timeoutall.go
│   │   │   │       ├── timeout.go
│   │   │   │       └── waitgoboring.go
│   │   │   ├── concurrency.slide
│   │   │   ├── go1
│   │   │   │   ├── changes.png
│   │   │   │   ├── errordiff1.png
│   │   │   │   ├── errordiff2.png
│   │   │   │   └── go1lines.png
│   │   │   ├── go1.slide
│   │   │   ├── go-docs
│   │   │   │   ├── blog.png
│   │   │   │   ├── codewalk.png
│   │   │   │   ├── faninboring.go
│   │   │   │   ├── gobyexample.png
│   │   │   │   ├── godoc1.png
│   │   │   │   ├── godoc.png
│   │   │   │   ├── gopkgdoc.png
│   │   │   │   ├── gowiki.png
│   │   │   │   ├── javadoc1.png
│   │   │   │   ├── javadoc.png
│   │   │   │   ├── lseek.png
│   │   │   │   ├── play.png
│   │   │   │   ├── seek.png
│   │   │   │   └── tour.png
│   │   │   ├── go-docs.slide
│   │   │   ├── goforc
│   │   │   │   ├── adder.go
│   │   │   │   ├── cat.go
│   │   │   │   ├── celsius.go
│   │   │   │   ├── channels.go
│   │   │   │   ├── communication1.go
│   │   │   │   ├── communication2.go
│   │   │   │   ├── consts.go
│   │   │   │   ├── decls.go
│   │   │   │   ├── example0.go
│   │   │   │   ├── example1.go
│   │   │   │   ├── example2.go
│   │   │   │   ├── forloop.go
│   │   │   │   ├── hello.go
│   │   │   │   ├── interface.go
│   │   │   │   ├── point.go
│   │   │   │   ├── stmts.go
│   │   │   │   ├── vars.go
│   │   │   │   ├── worker1.go
│   │   │   │   └── worker2.go
│   │   │   ├── goforc.slide
│   │   │   ├── insidepresent
│   │   │   │   ├── hello.go
│   │   │   │   ├── socket.go
│   │   │   │   ├── socket-simple.go
│   │   │   │   ├── websocket.go
│   │   │   │   ├── websocket.js
│   │   │   │   └── wire.html
│   │   │   ├── insidepresent.slide
│   │   │   ├── README
│   │   │   ├── simple
│   │   │   │   ├── flag.go
│   │   │   │   ├── gopher.jpg
│   │   │   │   ├── hello.go
│   │   │   │   ├── hello-web.go
│   │   │   │   ├── io
│   │   │   │   │   └── io.go
│   │   │   │   ├── json.go
│   │   │   │   ├── reader.go
│   │   │   │   ├── split.png
│   │   │   │   ├── test
│   │   │   │   │   └── string_test.go
│   │   │   │   ├── test.go
│   │   │   │   ├── time2.go
│   │   │   │   ├── time3.go
│   │   │   │   ├── time.go
│   │   │   │   └── webfront
│   │   │   │       ├── main.go
│   │   │   │       ├── server_test.go
│   │   │   │       └── testdata
│   │   │   │           └── index.html
│   │   │   ├── simple.slide
│   │   │   ├── splash
│   │   │   │   ├── appenginegophercolor.jpg
│   │   │   │   ├── datacenter.jpg
│   │   │   │   └── fire.jpg
│   │   │   ├── splash.article
│   │   │   ├── splash.slide
│   │   │   ├── tutorial
│   │   │   │   ├── 1get.go
│   │   │   │   ├── 2json.go
│   │   │   │   ├── 3func.go
│   │   │   │   ├── 4method.go
│   │   │   │   ├── golang.json
│   │   │   │   ├── hello.go
│   │   │   │   ├── jsonserve.go
│   │   │   │   ├── main.go
│   │   │   │   └── reddit
│   │   │   │       └── reddit.go
│   │   │   ├── tutorial.slide
│   │   │   ├── waza
│   │   │   │   ├── balance.go
│   │   │   │   ├── gopherchart.jpg
│   │   │   │   ├── gophercomplex0.jpg
│   │   │   │   ├── gophercomplex1.jpg
│   │   │   │   ├── gophercomplex2.jpg
│   │   │   │   ├── gophercomplex3.jpg
│   │   │   │   ├── gophercomplex4.jpg
│   │   │   │   ├── gophercomplex5.jpg
│   │   │   │   ├── gophercomplex6.jpg
│   │   │   │   ├── gophersimple1.jpg
│   │   │   │   ├── gophersimple2.jpg
│   │   │   │   ├── gophersimple3.jpg
│   │   │   │   ├── gophersimple4.jpg
│   │   │   │   ├── load1
│   │   │   │   ├── load2
│   │   │   │   └── snippets
│   │   │   ├── waza.slide
│   │   │   ├── zen
│   │   │   │   ├── hello.go
│   │   │   │   ├── http.go
│   │   │   │   ├── jsonformat.go
│   │   │   │   └── race.go
│   │   │   └── zen.slide
│   │   ├── 2013
│   │   │   ├── advconc
│   │   │   │   ├── buffer
│   │   │   │   │   └── buffer.go
│   │   │   │   ├── dedupermain
│   │   │   │   │   └── dedupermain.go
│   │   │   │   ├── fakemain
│   │   │   │   │   └── fakemain.go
│   │   │   │   ├── gopherhat.jpg
│   │   │   │   ├── gopherrunning.jpg
│   │   │   │   ├── gopherswim.jpg
│   │   │   │   ├── gopherswrench.jpg
│   │   │   │   ├── naivemain
│   │   │   │   │   └── naivemain.go
│   │   │   │   ├── nilselect
│   │   │   │   │   └── nilselect.go
│   │   │   │   ├── pingpong
│   │   │   │   │   └── pingpong.go
│   │   │   │   ├── pingpong1.go
│   │   │   │   ├── pingpongdeadlock
│   │   │   │   │   └── pingpongdeadlock.go
│   │   │   │   ├── pingpongpanic
│   │   │   │   │   └── pingpongpanic.go
│   │   │   │   ├── race.out
│   │   │   │   ├── race.png
│   │   │   │   └── realmain
│   │   │   │       └── realmain.go
│   │   │   ├── advconc.slide
│   │   │   ├── bestpractices
│   │   │   │   ├── bufchanfix.go
│   │   │   │   ├── bufchan.go
│   │   │   │   ├── cmd.png
│   │   │   │   ├── concurrency1.go
│   │   │   │   ├── concurrency2.go
│   │   │   │   ├── funcdraw
│   │   │   │   │   ├── cmd
│   │   │   │   │   │   └── funcdraw.go
│   │   │   │   │   ├── drawer
│   │   │   │   │   │   ├── dependent.go
│   │   │   │   │   │   ├── drawer.go
│   │   │   │   │   │   └── drawer_test.go
│   │   │   │   │   └── parser
│   │   │   │   │       └── parser.go
│   │   │   │   ├── httphandler.go
│   │   │   │   ├── quitchan.go
│   │   │   │   ├── server.go
│   │   │   │   ├── shortercode1.go
│   │   │   │   ├── shortercode2.go
│   │   │   │   ├── shortercode3.go
│   │   │   │   ├── shortercode4.go
│   │   │   │   ├── shortercode5.go
│   │   │   │   └── shortercode6.go
│   │   │   ├── bestpractices.slide
│   │   │   ├── distsys
│   │   │   │   ├── addr1.go
│   │   │   │   ├── addr2.go
│   │   │   │   ├── addr3.go
│   │   │   │   ├── addr4.go
│   │   │   │   ├── addr5.go
│   │   │   │   ├── finger.go
│   │   │   │   ├── hello0.go
│   │   │   │   ├── hello1.go
│   │   │   │   ├── hello.go
│   │   │   │   ├── replread.go
│   │   │   │   ├── replwrite.go
│   │   │   │   ├── writebuffer2.go
│   │   │   │   └── writebuffer.go
│   │   │   ├── distsys.slide
│   │   │   ├── go1.1
│   │   │   │   ├── blockprofile.png
│   │   │   │   ├── blockprofile.svg
│   │   │   │   ├── chanof.go
│   │   │   │   ├── intdiv.go
│   │   │   │   ├── makefunc.go
│   │   │   │   ├── methodvals.go
│   │   │   │   ├── methodvals-old.go
│   │   │   │   ├── race.go
│   │   │   │   ├── return.go
│   │   │   │   ├── return-old.go
│   │   │   │   ├── scanner2.go
│   │   │   │   ├── scanner.go
│   │   │   │   ├── timer.go
│   │   │   │   └── yearday.go
│   │   │   ├── go1.1.slide
│   │   │   ├── go4python
│   │   │   │   ├── decoex.go
│   │   │   │   ├── deco.go
│   │   │   │   ├── deco.py
│   │   │   │   ├── dyntyp.py
│   │   │   │   ├── fib-gen2.go
│   │   │   │   ├── fib-gen.go
│   │   │   │   ├── fib-gen.py
│   │   │   │   ├── fib.go
│   │   │   │   ├── fib.py
│   │   │   │   ├── genex2.go
│   │   │   │   ├── genex.go
│   │   │   │   ├── img
│   │   │   │   │   ├── duck.jpg
│   │   │   │   │   ├── fib-go.png
│   │   │   │   │   ├── fib-py.png
│   │   │   │   │   ├── funnelin.jpg
│   │   │   │   │   ├── gopher.jpg
│   │   │   │   │   └── monkey.jpg
│   │   │   │   ├── monkey.go
│   │   │   │   ├── monkey.py
│   │   │   │   └── typesandmethods.go
│   │   │   ├── go4python.slide
│   │   │   ├── go-sreops
│   │   │   │   ├── goroutines-channels.go
│   │   │   │   ├── goroutines.go
│   │   │   │   └── hello.go
│   │   │   ├── go-sreops.slide
│   │   │   ├── highperf
│   │   │   │   ├── aegopher.jpg
│   │   │   │   ├── appenginegophercolor.jpg
│   │   │   │   ├── appstats1.png
│   │   │   │   ├── appstats2.png
│   │   │   │   ├── appstats3.png
│   │   │   │   ├── art
│   │   │   │   │   ├── gophercart.png
│   │   │   │   │   ├── gophercheckout.png
│   │   │   │   │   └── gophermegaphone.png
│   │   │   │   ├── cachingembed.html
│   │   │   │   ├── concurrency.go.notouch
│   │   │   │   ├── gophermart2.png
│   │   │   │   ├── gophermart.png
│   │   │   │   ├── gopherrulespanner.png
│   │   │   │   ├── longtail.go
│   │   │   │   ├── mart
│   │   │   │   │   ├── 1
│   │   │   │   │   │   ├── app.yaml
│   │   │   │   │   │   └── mart.go
│   │   │   │   │   ├── 2
│   │   │   │   │   │   ├── app.yaml
│   │   │   │   │   │   └── mart.go
│   │   │   │   │   ├── 3
│   │   │   │   │   │   ├── app.yaml
│   │   │   │   │   │   └── mart.go
│   │   │   │   │   └── README
│   │   │   │   ├── santaembed.html
│   │   │   │   ├── santagraph.png
│   │   │   │   ├── santa.png
│   │   │   │   └── turkey.png
│   │   │   ├── highperf.slide
│   │   │   ├── oscon-dl
│   │   │   │   ├── after-code.png
│   │   │   │   ├── after.go
│   │   │   │   ├── after.png
│   │   │   │   ├── before.png
│   │   │   │   ├── chunkaligned.go
│   │   │   │   ├── copy.go
│   │   │   │   ├── cpp-toggle.png
│   │   │   │   ├── cpp-writeerr.png
│   │   │   │   ├── cpp-write.png
│   │   │   │   ├── crbug.png
│   │   │   │   ├── groupcache.go
│   │   │   │   ├── reader.png
│   │   │   │   ├── readseeker.png
│   │   │   │   ├── sectionreader.png
│   │   │   │   ├── seeker.png
│   │   │   │   ├── servecontent.png
│   │   │   │   ├── server-compose.go
│   │   │   │   ├── server-content.go
│   │   │   │   ├── server-fs.go
│   │   │   │   ├── server.go
│   │   │   │   ├── server-hello.go
│   │   │   │   ├── sizereaderat.go
│   │   │   │   └── slow.png
│   │   │   └── oscon-dl.slide
│   │   ├── 2014
│   │   │   ├── c2go.slide
│   │   │   ├── camlistore
│   │   │   │   ├── cam-android.png
│   │   │   │   ├── cam-boot.png
│   │   │   │   ├── cam-checkins.png
│   │   │   │   ├── cam-fuse.png
│   │   │   │   ├── cam-mix-types.png
│   │   │   │   ├── cam-moscow.png
│   │   │   │   ├── cam-other.png
│   │   │   │   ├── cam-pano.png
│   │   │   │   └── cam-paris-portrait.png
│   │   │   ├── camlistore.slide
│   │   │   ├── compiling
│   │   │   │   ├── const1.go
│   │   │   │   ├── const2.go
│   │   │   │   ├── const3.go
│   │   │   │   ├── name1.go
│   │   │   │   ├── name2.go
│   │   │   │   ├── rtype1.go
│   │   │   │   ├── rtype2.go
│   │   │   │   └── var1.go
│   │   │   ├── compiling.slide
│   │   │   ├── droidcon
│   │   │   │   ├── gopherswim.jpg
│   │   │   │   └── gopherswrench.jpg
│   │   │   ├── droidcon.slide
│   │   │   ├── go1.3
│   │   │   │   ├── json.png
│   │   │   │   ├── liblink1.png
│   │   │   │   ├── liblink2.png
│   │   │   │   └── liblink.graffle
│   │   │   ├── go1.3.slide
│   │   │   ├── go4gophers
│   │   │   │   ├── chain.go
│   │   │   │   ├── godoc.png
│   │   │   │   ├── gopherflag.png
│   │   │   │   ├── gopherhat.jpg
│   │   │   │   ├── gopherswim.jpg
│   │   │   │   ├── gopherswrench.jpg
│   │   │   │   ├── gophertraining.html
│   │   │   │   ├── gophertraining.png
│   │   │   │   ├── organs2.go
│   │   │   │   ├── organs3.go
│   │   │   │   ├── organs.go
│   │   │   │   ├── reader.go
│   │   │   │   ├── roshi.png
│   │   │   │   ├── sigourney.png
│   │   │   │   ├── sort.go
│   │   │   │   ├── tree-nothread.go
│   │   │   │   ├── tree.png
│   │   │   │   ├── tree-select.go
│   │   │   │   ├── tree-thread.go
│   │   │   │   └── tree-walk.go
│   │   │   ├── go4gophers.slide
│   │   │   ├── go4java
│   │   │   │   ├── BadInheritance.java
│   │   │   │   ├── battle.go
│   │   │   │   ├── chan.go
│   │   │   │   ├── Composition.java
│   │   │   │   ├── conc1.go
│   │   │   │   ├── conc2.go
│   │   │   │   ├── conc3.go
│   │   │   │   ├── embedsample.go
│   │   │   │   ├── goodcounter.go
│   │   │   │   ├── goroutines.go
│   │   │   │   ├── img
│   │   │   │   │   ├── baby.jpg
│   │   │   │   │   ├── badinheritance.png
│   │   │   │   │   ├── busy.jpg
│   │   │   │   │   ├── chain.jpg
│   │   │   │   │   ├── conc.jpg
│   │   │   │   │   ├── duck.jpg
│   │   │   │   │   ├── fast.jpg
│   │   │   │   │   ├── funcdraw.png
│   │   │   │   │   ├── funnelin.jpg
│   │   │   │   │   ├── gopher.jpg
│   │   │   │   │   ├── lego.jpg
│   │   │   │   │   ├── perfection.jpg
│   │   │   │   │   ├── piet.png
│   │   │   │   │   └── trends.png
│   │   │   │   ├── loopback.go
│   │   │   │   ├── runner
│   │   │   │   │   ├── embed.go
│   │   │   │   │   └── runner.go
│   │   │   │   └── writecounter.go
│   │   │   ├── go4java.slide
│   │   │   ├── gocon-tokyo
│   │   │   │   ├── 60p.jpg
│   │   │   │   ├── changestats.png
│   │   │   │   ├── concurrency0.svg
│   │   │   │   ├── concurrency.svg
│   │   │   │   ├── concurrent.jpg
│   │   │   │   ├── contig-stack.png
│   │   │   │   ├── docker.png
│   │   │   │   ├── drone.png
│   │   │   │   ├── funfast-nogo.svg
│   │   │   │   ├── funfast.svg
│   │   │   │   ├── generics.svg
│   │   │   │   ├── goandroid.png
│   │   │   │   ├── gpio.gif
│   │   │   │   ├── sigourney.png
│   │   │   │   ├── spaghetti.jpg
│   │   │   │   ├── tardis.png
│   │   │   │   └── trs.png
│   │   │   ├── gocon-tokyo.slide
│   │   │   ├── gotham-context
│   │   │   │   ├── after.go
│   │   │   │   ├── before.go
│   │   │   │   ├── eg.go
│   │   │   │   ├── first-context.go
│   │   │   │   ├── first.go
│   │   │   │   ├── interface.go
│   │   │   │   └── transitive.svg
│   │   │   ├── gotham-context.slide
│   │   │   ├── gothamgo-android
│   │   │   │   ├── red.go
│   │   │   │   ├── sprite_affine.svg
│   │   │   │   ├── sprite_subtex.svg
│   │   │   │   └── touch.go
│   │   │   ├── gothamgo-android.slide
│   │   │   ├── hammers
│   │   │   │   ├── codegen.go
│   │   │   │   ├── extractiface.go
│   │   │   │   ├── extractpath.go
│   │   │   │   ├── findthecode.go
│   │   │   │   ├── findtheifacedecl.go
│   │   │   │   ├── format.go
│   │   │   │   ├── fulltype.go
│   │   │   │   ├── importpath.go
│   │   │   │   └── types.go
│   │   │   ├── hammers.slide
│   │   │   ├── hellogophers
│   │   │   │   ├── emerging.png
│   │   │   │   ├── gophers.jpg
│   │   │   │   ├── hello_20080606.go
│   │   │   │   ├── hello_20080627.go
│   │   │   │   ├── hello_20080811.go
│   │   │   │   ├── hello_20081024.go
│   │   │   │   ├── hello_20090115.go
│   │   │   │   ├── hello_20091211.go
│   │   │   │   ├── helloAnsi.c
│   │   │   │   ├── hello.b
│   │   │   │   ├── hello.c
│   │   │   │   ├── helloDraftAnsi.c
│   │   │   │   ├── hello.go
│   │   │   │   ├── hellogophers.go
│   │   │   │   ├── helloKnR.c
│   │   │   │   ├── sieve_20080305.go
│   │   │   │   ├── sieve_20080722.go
│   │   │   │   ├── sieve_20080917.go
│   │   │   │   ├── sieve_20090106.go
│   │   │   │   ├── sieve_20090925.go
│   │   │   │   ├── sieve.csp
│   │   │   │   ├── sieve.go
│   │   │   │   ├── sieve.newsqueak
│   │   │   │   └── trends.png
│   │   │   ├── hellogophers.slide
│   │   │   ├── names.slide
│   │   │   ├── organizeio
│   │   │   │   ├── godoc.png
│   │   │   │   ├── gogetversion.png
│   │   │   │   ├── hello.go
│   │   │   │   └── home.png
│   │   │   ├── organizeio.slide
│   │   │   ├── playground
│   │   │   │   ├── deadlock.go
│   │   │   │   ├── file.go
│   │   │   │   ├── heap.go
│   │   │   │   ├── hello.go
│   │   │   │   ├── http.go
│   │   │   │   ├── img
│   │   │   │   │   ├── andrew.png
│   │   │   │   │   ├── arch.png
│   │   │   │   │   ├── areyousure.png
│   │   │   │   │   ├── blog.png
│   │   │   │   │   ├── brad.png
│   │   │   │   │   ├── bug.png
│   │   │   │   │   ├── cat.jpg
│   │   │   │   │   ├── examples.png
│   │   │   │   │   ├── gopherbw.png
│   │   │   │   │   ├── jan.png
│   │   │   │   │   ├── mattn.png
│   │   │   │   │   ├── nacl.png
│   │   │   │   │   ├── play.png
│   │   │   │   │   ├── share.png
│   │   │   │   │   ├── sleepbug.png
│   │   │   │   │   └── tour.png
│   │   │   │   ├── loop.go
│   │   │   │   ├── net.go
│   │   │   │   ├── removeall.go
│   │   │   │   ├── rm.go
│   │   │   │   ├── sleepfast.go
│   │   │   │   ├── sleep.go
│   │   │   │   └── stack.go
│   │   │   ├── playground.slide
│   │   │   ├── readability
│   │   │   │   ├── close-cond-bad.go
│   │   │   │   ├── close-cond-good.go
│   │   │   │   ├── err_close_write_bad.go
│   │   │   │   ├── err_close_write_good.go
│   │   │   │   ├── err_regexp_bad.go
│   │   │   │   ├── err_regexp_good.go
│   │   │   │   ├── example_test.go
│   │   │   │   ├── gopher-ok-no.png
│   │   │   │   ├── gophers5th.jpg
│   │   │   │   ├── if-else-bad.go
│   │   │   │   ├── if-else-good.go
│   │   │   │   ├── if-switch-bad.go
│   │   │   │   ├── if-switch-good.go
│   │   │   │   ├── implement-interface-bad.go
│   │   │   │   ├── implement-interface-good.go
│   │   │   │   ├── in-band-error-client.go
│   │   │   │   ├── in-band-error.go
│   │   │   │   ├── long-line-fold.go
│   │   │   │   ├── long-line-nofold.go
│   │   │   │   ├── long-line-short.go
│   │   │   │   ├── nil_error.go
│   │   │   │   ├── nil_interface_en.go
│   │   │   │   ├── pkg.png
│   │   │   │   ├── project.png
│   │   │   │   ├── reflect-bad.go
│   │   │   │   ├── reflect-good.go
│   │   │   │   ├── ref.png
│   │   │   │   ├── resthandler-fix2.go
│   │   │   │   ├── resthandler.go
│   │   │   │   ├── struct-field-bad.go
│   │   │   │   ├── struct-field-good.go
│   │   │   │   ├── talks.png
│   │   │   │   ├── test-pattern_en.go
│   │   │   │   ├── time_duration_bad1.go
│   │   │   │   ├── time_duration_bad2.go
│   │   │   │   ├── time_duration_bad.go
│   │   │   │   ├── time_duration_good.go
│   │   │   │   └── val-and-error.go
│   │   │   ├── readability.slide
│   │   │   ├── research2
│   │   │   │   ├── addr1.go
│   │   │   │   ├── addr2.go
│   │   │   │   ├── busy.jpg
│   │   │   │   ├── csmith.png
│   │   │   │   ├── datacenter.jpg
│   │   │   │   ├── emoji.png
│   │   │   │   ├── gophercomplex6.jpg
│   │   │   │   ├── gopherswrench.jpg
│   │   │   │   ├── hello.go
│   │   │   │   ├── race.png
│   │   │   │   └── select.go
│   │   │   ├── research2.slide
│   │   │   ├── research.slide
│   │   │   ├── state-of-go
│   │   │   │   ├── bus.jpg
│   │   │   │   ├── dotgo.png
│   │   │   │   ├── gophercon.png
│   │   │   │   ├── gophers.jpg
│   │   │   │   ├── indent.png
│   │   │   │   ├── india.png
│   │   │   │   ├── msg-exceptions1b.png
│   │   │   │   ├── msg-exceptions2.png
│   │   │   │   ├── msg-generics.png
│   │   │   │   ├── msg-lacks.png
│   │   │   │   ├── msg-logo1.png
│   │   │   │   ├── msg-logo2.png
│   │   │   │   ├── msg-logo3.jpg
│   │   │   │   ├── msg-nogenerics.png
│   │   │   │   ├── msg-semi.png
│   │   │   │   ├── msg-type.png
│   │   │   │   ├── msg-wrong.png
│   │   │   │   ├── oloh.png
│   │   │   │   ├── redmonk.png
│   │   │   │   ├── sadgopher.png
│   │   │   │   └── tattoo.jpg
│   │   │   ├── state-of-go.slide
│   │   │   ├── state-of-the-gopher
│   │   │   │   ├── build.png
│   │   │   │   ├── bus.jpg
│   │   │   │   ├── contig-stack.png
│   │   │   │   ├── dotgo.png
│   │   │   │   ├── gophercon.png
│   │   │   │   ├── gopher.jpg
│   │   │   │   ├── india.png
│   │   │   │   ├── oloh.png
│   │   │   │   ├── opensource.png
│   │   │   │   ├── trace.png
│   │   │   │   ├── website1.png
│   │   │   │   └── website2.png
│   │   │   ├── state-of-the-gopher.slide
│   │   │   ├── static-analysis
│   │   │   │   ├── demo.go
│   │   │   │   ├── demoscript
│   │   │   │   ├── egtest
│   │   │   │   │   └── test.go
│   │   │   │   ├── fib.go
│   │   │   │   ├── hello.go
│   │   │   │   ├── hvn.svg
│   │   │   │   ├── template.go
│   │   │   │   └── tools.svg
│   │   │   ├── static-analysis.slide
│   │   │   ├── taste
│   │   │   │   ├── concurrency1.go
│   │   │   │   ├── concurrency2.go
│   │   │   │   ├── examples.go
│   │   │   │   ├── hello.go
│   │   │   │   ├── hellohttp.go
│   │   │   │   ├── histo0.go
│   │   │   │   ├── histo.go
│   │   │   │   ├── histop.go
│   │   │   │   ├── idents.go
│   │   │   │   ├── point.go
│   │   │   │   ├── sort.go
│   │   │   │   ├── stringer.go
│   │   │   │   ├── walk.go
│   │   │   │   └── weekday.go
│   │   │   ├── taste.slide
│   │   │   ├── testing
│   │   │   │   ├── cover.png
│   │   │   │   ├── go1.1.png
│   │   │   │   ├── httprecorder.go
│   │   │   │   ├── httpserver.go
│   │   │   │   ├── subprocess
│   │   │   │   │   ├── subprocess.go
│   │   │   │   │   └── subprocess_test.go
│   │   │   │   ├── test1
│   │   │   │   │   └── string_test.go
│   │   │   │   └── test2
│   │   │   │       └── string_test.go
│   │   │   └── testing.slide
│   │   ├── 2015
│   │   │   ├── dynamic-tools
│   │   │   │   ├── algo.png
│   │   │   │   ├── go-fuzz.png
│   │   │   │   ├── philosoraptor.png
│   │   │   │   ├── trace.png
│   │   │   │   └── tracer.png
│   │   │   ├── dynamic-tools.slide
│   │   │   ├── go4cpp
│   │   │   │   ├── badcounter.go
│   │   │   │   ├── battle.go
│   │   │   │   ├── busy.jpg
│   │   │   │   ├── chain.jpg
│   │   │   │   ├── chan.go
│   │   │   │   ├── conc1.go
│   │   │   │   ├── conc2.go
│   │   │   │   ├── conc3.go
│   │   │   │   ├── conc.jpg
│   │   │   │   ├── defer.go
│   │   │   │   ├── diamond.go
│   │   │   │   ├── duck.jpg
│   │   │   │   ├── embedding.go
│   │   │   │   ├── funcdraw.png
│   │   │   │   ├── funnelin.jpg
│   │   │   │   ├── goodcounter.go
│   │   │   │   ├── goroutines.go
│   │   │   │   ├── mock.go
│   │   │   │   ├── sizes.go
│   │   │   │   ├── trends.png
│   │   │   │   └── webserver.go
│   │   │   ├── go4cpp.slide
│   │   │   ├── gofmt
│   │   │   │   ├── biggerpic.jpg
│   │   │   │   ├── bigpic.jpg
│   │   │   │   ├── comments.jpg
│   │   │   │   ├── merge.jpg
│   │   │   │   └── tabstops.jpg
│   │   │   ├── gofmt-cn.slide
│   │   │   ├── gofmt-en.slide
│   │   │   ├── go-for-java-programmers
│   │   │   │   ├── builtin.go
│   │   │   │   ├── channel.go
│   │   │   │   ├── closure.go
│   │   │   │   ├── error.go
│   │   │   │   ├── first.go
│   │   │   │   ├── frontend.go
│   │   │   │   ├── frontend-screenshot.png
│   │   │   │   ├── func.go
│   │   │   │   ├── gofmt-after.go
│   │   │   │   ├── goimports-after.go
│   │   │   │   ├── goimports-before.go
│   │   │   │   ├── google14.jpg
│   │   │   │   ├── google17.jpg
│   │   │   │   ├── google1.jpg
│   │   │   │   ├── google20.jpg
│   │   │   │   ├── google-first.go
│   │   │   │   ├── google-parallel.go
│   │   │   │   ├── google-serial.go
│   │   │   │   ├── google-timeout.go
│   │   │   │   ├── goroutine.go
│   │   │   │   ├── hello
│   │   │   │   │   ├── hello.go
│   │   │   │   │   ├── Main.class
│   │   │   │   │   ├── Main.java
│   │   │   │   │   └── server.go
│   │   │   │   ├── interface.go
│   │   │   │   ├── method.go
│   │   │   │   ├── panic.go
│   │   │   │   ├── pingpipe.go
│   │   │   │   ├── pingpong.go
│   │   │   │   ├── pingselect.go
│   │   │   │   ├── player.go
│   │   │   │   ├── pointer.go
│   │   │   │   ├── safe.go
│   │   │   │   ├── spdy.png
│   │   │   │   └── struct.go
│   │   │   ├── go-for-java-programmers.slide
│   │   │   ├── go-gc.pdf
│   │   │   ├── gogo.slide
│   │   │   ├── gophercon-goevolution
│   │   │   │   ├── GopherEvolution.svg
│   │   │   │   └── HoaresPLHints.JPG
│   │   │   ├── gophercon-goevolution.slide
│   │   │   ├── gophercon-go-on-mobile
│   │   │   │   ├── androidstudio2.png
│   │   │   │   ├── canihas.jpg
│   │   │   │   ├── caution.png
│   │   │   │   ├── contributors.png
│   │   │   │   ├── gobind.png
│   │   │   │   ├── gophercloud.png
│   │   │   │   ├── ivyabout.png
│   │   │   │   ├── ivymobile.png
│   │   │   │   ├── ivyscreenshot2.png
│   │   │   │   ├── memegobind.jpg
│   │   │   │   └── README
│   │   │   ├── gophercon-go-on-mobile.slide
│   │   │   ├── gotham-grpc
│   │   │   │   ├── backend
│   │   │   │   │   └── backend.go
│   │   │   │   ├── backend.svg
│   │   │   │   ├── client
│   │   │   │   │   └── client.go
│   │   │   │   ├── client.svg
│   │   │   │   ├── frontend
│   │   │   │   │   └── frontend.go
│   │   │   │   ├── frontend.svg
│   │   │   │   ├── search
│   │   │   │   │   ├── README.md
│   │   │   │   │   ├── search.pb.go
│   │   │   │   │   └── search.proto
│   │   │   │   ├── search-only
│   │   │   │   │   ├── README.md
│   │   │   │   │   ├── search-only.pb.go
│   │   │   │   │   └── search-only.proto
│   │   │   │   ├── search.svg
│   │   │   │   ├── system.svg
│   │   │   │   └── watch.svg
│   │   │   ├── gotham-grpc.slide
│   │   │   ├── how-go-was-made
│   │   │   │   ├── 5years.png
│   │   │   │   ├── errors-discussion.png
│   │   │   │   ├── errors-final.png
│   │   │   │   ├── errors-issue.png
│   │   │   │   ├── errors-rog.png
│   │   │   │   ├── gopherswrench.jpg
│   │   │   │   ├── mapchan.diff
│   │   │   │   ├── reflect1.png
│   │   │   │   ├── reflect2.png
│   │   │   │   ├── reflect3.png
│   │   │   │   ├── trends.png
│   │   │   │   └── website.png
│   │   │   ├── how-go-was-made.slide
│   │   │   ├── json
│   │   │   │   ├── dates.go
│   │   │   │   ├── img
│   │   │   │   │   └── mindblown.gif
│   │   │   │   ├── roman_numerals.go
│   │   │   │   ├── secret.go
│   │   │   │   ├── unmarshaler0bad.go
│   │   │   │   ├── unmarshaler0.go
│   │   │   │   ├── unmarshaler0map.go
│   │   │   │   ├── unmarshaler1.go
│   │   │   │   ├── unmarshaler2.go
│   │   │   │   ├── unmarshaler3.go
│   │   │   │   └── unmarshaler4.go
│   │   │   ├── json.slide
│   │   │   ├── keeping-up
│   │   │   │   ├── backend_interface.diff
│   │   │   │   ├── cst.gcc
│   │   │   │   ├── escape.go
│   │   │   │   ├── escape.png
│   │   │   │   ├── gccgo_structure.png
│   │   │   │   ├── go_build.log
│   │   │   │   └── gource_explosion.html
│   │   │   ├── keeping-up.slide
│   │   │   ├── simplicity-is-complicated
│   │   │   │   ├── gophers.jpg
│   │   │   │   ├── gopherslide2smblue.jpg
│   │   │   │   ├── gopherslide2smbrown.jpg
│   │   │   │   ├── gopherslide2sm.jpg
│   │   │   │   ├── hello.go
│   │   │   │   └── shift.go
│   │   │   ├── simplicity-is-complicated.slide
│   │   │   ├── state-of-go
│   │   │   │   ├── gala.jpg
│   │   │   │   └── trace.png
│   │   │   ├── state-of-go-may
│   │   │   │   ├── conc-bench.png
│   │   │   │   ├── conc-chain.png
│   │   │   │   ├── conc-powser.png
│   │   │   │   ├── conc-practical.png
│   │   │   │   ├── conc-sieve.png
│   │   │   │   ├── gc2.png
│   │   │   │   ├── gcperf.png
│   │   │   │   ├── gc.png
│   │   │   │   ├── go1bench.svg
│   │   │   │   ├── gophercon.png
│   │   │   │   ├── iphone.jpg
│   │   │   │   └── perfchart.png
│   │   │   ├── state-of-go-may.slide
│   │   │   ├── state-of-go.slide
│   │   │   ├── tricks
│   │   │   │   ├── anon-interface.go
│   │   │   │   ├── broadcastwriter
│   │   │   │   │   └── broadcastwriter.go
│   │   │   │   ├── compare2.go
│   │   │   │   ├── compare.go
│   │   │   │   ├── compare-map.go
│   │   │   │   ├── cons.go
│   │   │   │   ├── embed.go
│   │   │   │   ├── json-decode.go
│   │   │   │   ├── json-encode.go
│   │   │   │   ├── json-nest.go
│   │   │   │   ├── method-http.go
│   │   │   │   ├── method-once.go
│   │   │   │   ├── method-values-1.go
│   │   │   │   ├── method-values-2.go
│   │   │   │   ├── repeated2.go
│   │   │   │   ├── repeated.go
│   │   │   │   ├── string_test2.go
│   │   │   │   ├── string_test.go
│   │   │   │   ├── subprocess
│   │   │   │   │   ├── subprocess.go
│   │   │   │   │   └── subprocess_test.go
│   │   │   │   ├── template.go
│   │   │   │   └── time-deps.png
│   │   │   ├── tricks.slide
│   │   │   └── using-go-types-for-tools.html
│   │   ├── 2016
│   │   │   ├── applicative
│   │   │   │   ├── builtin.go
│   │   │   │   ├── channel.go
│   │   │   │   ├── closure.go
│   │   │   │   ├── error.go
│   │   │   │   ├── first.go
│   │   │   │   ├── frontend.go
│   │   │   │   ├── frontend-screenshot.png
│   │   │   │   ├── func.go
│   │   │   │   ├── gofmt-after.go
│   │   │   │   ├── goimports-after.go
│   │   │   │   ├── goimports-before.go
│   │   │   │   ├── google
│   │   │   │   │   ├── fake.go
│   │   │   │   │   ├── first.go
│   │   │   │   │   ├── parallel.go
│   │   │   │   │   ├── serial.go
│   │   │   │   │   └── timeout.go
│   │   │   │   ├── google14.jpg
│   │   │   │   ├── google17.jpg
│   │   │   │   ├── google1.jpg
│   │   │   │   ├── google20.jpg
│   │   │   │   ├── google-parallel.go
│   │   │   │   ├── google-replicated.go
│   │   │   │   ├── google-serial.go
│   │   │   │   ├── google-timeout.go
│   │   │   │   ├── goroutine.go
│   │   │   │   ├── hello
│   │   │   │   │   ├── hello.go
│   │   │   │   │   ├── Main.class
│   │   │   │   │   ├── Main.java
│   │   │   │   │   └── server.go
│   │   │   │   ├── interface.go
│   │   │   │   ├── method.go
│   │   │   │   ├── panic.go
│   │   │   │   ├── pingpipe.go
│   │   │   │   ├── pingpong.go
│   │   │   │   ├── pingselect.go
│   │   │   │   ├── player.go
│   │   │   │   ├── pointer.go
│   │   │   │   ├── safe.go
│   │   │   │   ├── spdy.png
│   │   │   │   └── struct.go
│   │   │   ├── applicative.slide
│   │   │   ├── asm
│   │   │   │   ├── 360.s.txt
│   │   │   │   ├── 386.s.txt
│   │   │   │   ├── 68000.s.txt
│   │   │   │   ├── add.go
│   │   │   │   ├── amd64.s.txt
│   │   │   │   ├── apollo.s.txt
│   │   │   │   ├── arch1.png
│   │   │   │   ├── arch2.png
│   │   │   │   ├── arch386._go
│   │   │   │   ├── arm64.s.txt
│   │   │   │   ├── arm.s.txt
│   │   │   │   ├── cray1.s.txt
│   │   │   │   ├── mips64.s.txt
│   │   │   │   ├── pdp10.s.txt
│   │   │   │   ├── pdp11.s.txt
│   │   │   │   ├── ppc64le.s.txt
│   │   │   │   └── s390x.s.txt
│   │   │   ├── asm.slide
│   │   │   ├── prototype-your-design.pdf
│   │   │   ├── prototype-your-design.txt
│   │   │   ├── refactor
│   │   │   │   ├── atomic.graffle
│   │   │   │   ├── atomic.html
│   │   │   │   ├── atomic.svg
│   │   │   │   ├── gradual.graffle
│   │   │   │   ├── gradual.html
│   │   │   │   ├── gradual.svg
│   │   │   │   ├── import1.graffle
│   │   │   │   ├── import1.html
│   │   │   │   ├── import1.svg
│   │   │   │   ├── import2.graffle
│   │   │   │   ├── import2.html
│   │   │   │   ├── import2.svg
│   │   │   │   ├── template.html
│   │   │   │   ├── version1.graffle
│   │   │   │   ├── version1.html
│   │   │   │   ├── version1.svg
│   │   │   │   ├── version2.graffle
│   │   │   │   ├── version2.html
│   │   │   │   └── version2.svg
│   │   │   ├── refactor.article
│   │   │   ├── state-of-go
│   │   │   │   ├── cgo
│   │   │   │   │   └── main.go
│   │   │   │   ├── govet
│   │   │   │   │   └── main.go
│   │   │   │   ├── img
│   │   │   │   │   ├── bench1.png
│   │   │   │   │   ├── bench4.png
│   │   │   │   │   ├── bench-sort.png
│   │   │   │   │   ├── gc345.png
│   │   │   │   │   ├── gc56.png
│   │   │   │   │   ├── gcgotip.png
│   │   │   │   │   ├── minorchanges.png
│   │   │   │   │   ├── party-gopher.png
│   │   │   │   │   ├── twitter1.png
│   │   │   │   │   ├── twitter2.png
│   │   │   │   │   └── twitter3.png
│   │   │   │   ├── runtime
│   │   │   │   │   ├── crash.go
│   │   │   │   │   └── good
│   │   │   │   │       └── good.go
│   │   │   │   ├── sort
│   │   │   │   │   ├── stable.go
│   │   │   │   │   └── unstable.go
│   │   │   │   ├── template
│   │   │   │   │   ├── blocks.go
│   │   │   │   │   ├── define.go
│   │   │   │   │   ├── fixed.go
│   │   │   │   │   ├── new.go
│   │   │   │   │   ├── old.go
│   │   │   │   │   └── redefine.go
│   │   │   │   └── time
│   │   │   │       └── time.go
│   │   │   ├── state-of-go.slide
│   │   │   └── token.slide
│   │   ├── 2017
│   │   │   ├── exporting-go.pdf
│   │   │   ├── state-of-go
│   │   │   │   ├── img
│   │   │   │   │   ├── bench_log.png
│   │   │   │   │   ├── benchmark.png
│   │   │   │   │   ├── bench.png
│   │   │   │   │   ├── cgo.png
│   │   │   │   │   ├── defer.png
│   │   │   │   │   ├── flying.png
│   │   │   │   │   ├── gct1.png
│   │   │   │   │   ├── gct2.png
│   │   │   │   │   ├── gct3.png
│   │   │   │   │   ├── gct4.png
│   │   │   │   │   ├── gct5.png
│   │   │   │   │   ├── gctcpu.png
│   │   │   │   │   ├── http2.png
│   │   │   │   │   ├── http.png
│   │   │   │   │   ├── meetups.png
│   │   │   │   │   ├── more.png
│   │   │   │   │   ├── mutex_all.png
│   │   │   │   │   ├── mutex_all_zoom.png
│   │   │   │   │   ├── mutex_noprofile.png
│   │   │   │   │   ├── mutex_procs.png
│   │   │   │   │   ├── mutex_profile.png
│   │   │   │   │   ├── party-gopher.png
│   │   │   │   │   └── wwg.png
│   │   │   │   ├── runtime
│   │   │   │   │   ├── mapcrash.go
│   │   │   │   │   └── mutex
│   │   │   │   │       ├── main.go
│   │   │   │   │       ├── main_test.go
│   │   │   │   │       ├── mutex.out
│   │   │   │   │       └── mutex.test
│   │   │   │   ├── stdlib
│   │   │   │   │   ├── http2
│   │   │   │   │   │   ├── cert.pem
│   │   │   │   │   │   ├── http2.go
│   │   │   │   │   │   └── key.pem
│   │   │   │   │   ├── json_old.go
│   │   │   │   │   ├── plugin
│   │   │   │   │   │   ├── main.go
│   │   │   │   │   │   └── plugin.go
│   │   │   │   │   ├── shutdown.go
│   │   │   │   │   └── sort
│   │   │   │   │       └── sort_test.go
│   │   │   │   └── tools
│   │   │   │       ├── gobug.sh
│   │   │   │       ├── gofix.go
│   │   │   │       ├── gofix.sh
│   │   │   │       ├── govet.go
│   │   │   │       └── govet.sh
│   │   │   ├── state-of-go-aug.pdf
│   │   │   ├── state-of-go-may
│   │   │   │   ├── alias
│   │   │   │   │   └── main.go
│   │   │   │   ├── bits
│   │   │   │   │   └── main.go
│   │   │   │   ├── exec
│   │   │   │   │   ├── getenv
│   │   │   │   │   │   └── main.go
│   │   │   │   │   └── main.go
│   │   │   │   ├── html
│   │   │   │   │   └── main.go
│   │   │   │   ├── img
│   │   │   │   │   ├── atomic.svg
│   │   │   │   │   ├── benchmark.png
│   │   │   │   │   ├── exec-poll.png
│   │   │   │   │   ├── flying.png
│   │   │   │   │   ├── gradual.svg
│   │   │   │   │   ├── meetups.png
│   │   │   │   │   ├── quaternions.png
│   │   │   │   │   ├── twitter-poll.png
│   │   │   │   │   ├── wwg-logo.png
│   │   │   │   │   └── wwg.png
│   │   │   │   └── syncmap
│   │   │   │       └── main.go
│   │   │   ├── state-of-go-may.slide
│   │   │   └── state-of-go.slide
│   │   └── 2019
│   │       └── playground-v3
│   │           ├── arch.png
│   │           ├── cos.png
│   │           ├── hello.png
│   │           ├── pic.png
│   │           ├── playground-v3.slide
│   │           └── time.png
│   ├── CONTRIBUTING.md
│   ├── CONTRIBUTORS
│   ├── go.mod
│   ├── LICENSE
│   ├── PATENTS
│   └── README
├── tar
│   ├── blog-master.tar.gz
│   ├── crypto-master.tar.gz
│   ├── exp-master.tar.gz
│   ├── image-master.tar.gz
│   ├── mobile-master.tar.gz
│   ├── net-master.tar.gz
│   ├── sys-master.tar.gz
│   ├── talks-master.tar.gz
│   ├── text-master.tar.gz
│   └── tools-master.tar.gz
├── text
│   ├── AUTHORS
│   ├── cases
│   │   ├── cases.go
│   │   ├── context.go
│   │   ├── context_test.go
│   │   ├── example_test.go
│   │   ├── fold.go
│   │   ├── fold_test.go
│   │   ├── gen.go
│   │   ├── gen_trieval.go
│   │   ├── icu.go
│   │   ├── icu_test.go
│   │   ├── info.go
│   │   ├── map.go
│   │   ├── map_test.go
│   │   ├── tables10.0.0.go
│   │   ├── tables10.0.0_test.go
│   │   ├── tables11.0.0.go
│   │   ├── tables11.0.0_test.go
│   │   ├── tables12.0.0.go
│   │   ├── tables12.0.0_test.go
│   │   ├── tables9.0.0.go
│   │   ├── tables9.0.0_test.go
│   │   └── trieval.go
│   ├── cmd
│   │   └── gotext
│   │       ├── common.go
│   │       ├── doc.go
│   │       ├── examples
│   │       │   ├── extract
│   │       │   │   ├── catalog.go
│   │       │   │   ├── locales
│   │       │   │   │   ├── de
│   │       │   │   │   │   ├── messages.gotext.json
│   │       │   │   │   │   └── out.gotext.json
│   │       │   │   │   ├── en-US
│   │       │   │   │   │   ├── messages.gotext.json
│   │       │   │   │   │   └── out.gotext.json
│   │       │   │   │   └── zh
│   │       │   │   │       ├── messages.gotext.json
│   │       │   │   │       └── out.gotext.json
│   │       │   │   └── main.go
│   │       │   ├── extract_http
│   │       │   │   ├── catalog_gen.go
│   │       │   │   ├── locales
│   │       │   │   │   ├── de
│   │       │   │   │   │   └── out.gotext.json
│   │       │   │   │   ├── en
│   │       │   │   │   │   └── out.gotext.json
│   │       │   │   │   ├── en-US
│   │       │   │   │   │   └── out.gotext.json
│   │       │   │   │   └── zh
│   │       │   │   │       └── out.gotext.json
│   │       │   │   ├── main.go
│   │       │   │   └── pkg
│   │       │   │       └── pkg.go
│   │       │   └── rewrite
│   │       │       ├── main.go
│   │       │       └── printer.go
│   │       ├── extract.go
│   │       ├── generate.go
│   │       ├── main.go
│   │       ├── rewrite.go
│   │       └── update.go
│   ├── codereview.cfg
│   ├── collate
│   │   ├── build
│   │   │   ├── builder.go
│   │   │   ├── builder_test.go
│   │   │   ├── colelem.go
│   │   │   ├── colelem_test.go
│   │   │   ├── contract.go
│   │   │   ├── contract_test.go
│   │   │   ├── order.go
│   │   │   ├── order_test.go
│   │   │   ├── table.go
│   │   │   ├── trie.go
│   │   │   └── trie_test.go
│   │   ├── collate.go
│   │   ├── collate_test.go
│   │   ├── export_test.go
│   │   ├── index.go
│   │   ├── maketables.go
│   │   ├── option.go
│   │   ├── option_test.go
│   │   ├── reg_test.go
│   │   ├── sort.go
│   │   ├── sort_test.go
│   │   ├── tables.go
│   │   ├── table_test.go
│   │   └── tools
│   │       └── colcmp
│   │           ├── chars.go
│   │           ├── colcmp.go
│   │           ├── col.go
│   │           ├── darwin.go
│   │           ├── gen.go
│   │           ├── icu.go
│   │           └── Makefile
│   ├── CONTRIBUTING.md
│   ├── CONTRIBUTORS
│   ├── currency
│   │   ├── common.go
│   │   ├── currency.go
│   │   ├── currency_test.go
│   │   ├── example_test.go
│   │   ├── format.go
│   │   ├── format_test.go
│   │   ├── gen_common.go
│   │   ├── gen.go
│   │   ├── query.go
│   │   ├── query_test.go
│   │   ├── tables.go
│   │   └── tables_test.go
│   ├── date
│   │   ├── data_test.go
│   │   ├── gen.go
│   │   ├── gen_test.go
│   │   └── tables.go
│   ├── doc.go
│   ├── encoding
│   │   ├── charmap
│   │   │   ├── charmap.go
│   │   │   ├── charmap_test.go
│   │   │   ├── maketables.go
│   │   │   └── tables.go
│   │   ├── encoding.go
│   │   ├── encoding_test.go
│   │   ├── example_test.go
│   │   ├── htmlindex
│   │   │   ├── gen.go
│   │   │   ├── htmlindex.go
│   │   │   ├── htmlindex_test.go
│   │   │   ├── map.go
│   │   │   └── tables.go
│   │   ├── ianaindex
│   │   │   ├── example_test.go
│   │   │   ├── gen.go
│   │   │   ├── ianaindex.go
│   │   │   ├── ianaindex_test.go
│   │   │   └── tables.go
│   │   ├── internal
│   │   │   ├── enctest
│   │   │   │   └── enctest.go
│   │   │   ├── identifier
│   │   │   │   ├── gen.go
│   │   │   │   ├── identifier.go
│   │   │   │   └── mib.go
│   │   │   └── internal.go
│   │   ├── japanese
│   │   │   ├── all.go
│   │   │   ├── all_test.go
│   │   │   ├── eucjp.go
│   │   │   ├── iso2022jp.go
│   │   │   ├── maketables.go
│   │   │   ├── shiftjis.go
│   │   │   └── tables.go
│   │   ├── korean
│   │   │   ├── all_test.go
│   │   │   ├── euckr.go
│   │   │   ├── maketables.go
│   │   │   └── tables.go
│   │   ├── simplifiedchinese
│   │   │   ├── all.go
│   │   │   ├── all_test.go
│   │   │   ├── gbk.go
│   │   │   ├── hzgb2312.go
│   │   │   ├── maketables.go
│   │   │   └── tables.go
│   │   ├── testdata
│   │   │   ├── candide-gb18030.txt
│   │   │   ├── candide-utf-16le.txt
│   │   │   ├── candide-utf-32be.txt
│   │   │   ├── candide-utf-8.txt
│   │   │   ├── candide-windows-1252.txt
│   │   │   ├── rashomon-euc-jp.txt
│   │   │   ├── rashomon-iso-2022-jp.txt
│   │   │   ├── rashomon-shift-jis.txt
│   │   │   ├── rashomon-utf-8.txt
│   │   │   ├── sunzi-bingfa-gb-levels-1-and-2-hz-gb2312.txt
│   │   │   ├── sunzi-bingfa-gb-levels-1-and-2-utf-8.txt
│   │   │   ├── sunzi-bingfa-simplified-gbk.txt
│   │   │   ├── sunzi-bingfa-simplified-utf-8.txt
│   │   │   ├── sunzi-bingfa-traditional-big5.txt
│   │   │   ├── sunzi-bingfa-traditional-utf-8.txt
│   │   │   ├── unsu-joh-eun-nal-euc-kr.txt
│   │   │   └── unsu-joh-eun-nal-utf-8.txt
│   │   ├── traditionalchinese
│   │   │   ├── all_test.go
│   │   │   ├── big5.go
│   │   │   ├── maketables.go
│   │   │   └── tables.go
│   │   └── unicode
│   │       ├── override.go
│   │       ├── unicode.go
│   │       ├── unicode_test.go
│   │       └── utf32
│   │           ├── utf32.go
│   │           └── utf32_test.go
│   ├── feature
│   │   └── plural
│   │       ├── common.go
│   │       ├── data_test.go
│   │       ├── example_test.go
│   │       ├── gen_common.go
│   │       ├── gen.go
│   │       ├── message.go
│   │       ├── message_test.go
│   │       ├── plural.go
│   │       ├── plural_test.go
│   │       └── tables.go
│   ├── gen.go
│   ├── go.mod
│   ├── go.sum
│   ├── internal
│   │   ├── catmsg
│   │   │   ├── catmsg.go
│   │   │   ├── catmsg_test.go
│   │   │   ├── codec.go
│   │   │   ├── varint.go
│   │   │   └── varint_test.go
│   │   ├── cldrtree
│   │   │   ├── cldrtree.go
│   │   │   ├── cldrtree_test.go
│   │   │   ├── generate.go
│   │   │   ├── option.go
│   │   │   ├── testdata
│   │   │   │   ├── test1
│   │   │   │   │   ├── common
│   │   │   │   │   │   └── main
│   │   │   │   │   │       └── root.xml
│   │   │   │   │   └── output.go
│   │   │   │   └── test2
│   │   │   │       ├── common
│   │   │   │       │   └── main
│   │   │   │       │       ├── en_001.xml
│   │   │   │       │       ├── en_GB.xml
│   │   │   │       │       ├── en.xml
│   │   │   │       │       └── root.xml
│   │   │   │       └── output.go
│   │   │   ├── tree.go
│   │   │   └── type.go
│   │   ├── colltab
│   │   │   ├── collate_test.go
│   │   │   ├── collelem.go
│   │   │   ├── collelem_test.go
│   │   │   ├── colltab.go
│   │   │   ├── colltab_test.go
│   │   │   ├── contract.go
│   │   │   ├── contract_test.go
│   │   │   ├── iter.go
│   │   │   ├── iter_test.go
│   │   │   ├── numeric.go
│   │   │   ├── numeric_test.go
│   │   │   ├── table.go
│   │   │   ├── trie.go
│   │   │   ├── trie_test.go
│   │   │   ├── weighter.go
│   │   │   └── weighter_test.go
│   │   ├── export
│   │   │   ├── idna
│   │   │   │   ├── common_test.go
│   │   │   │   ├── conformance_test.go
│   │   │   │   ├── example_test.go
│   │   │   │   ├── gen10.0.0_test.go
│   │   │   │   ├── gen9.0.0_test.go
│   │   │   │   ├── gen_common.go
│   │   │   │   ├── gen.go
│   │   │   │   ├── gen_trieval.go
│   │   │   │   ├── idna10.0.0.go
│   │   │   │   ├── idna10.0.0_test.go
│   │   │   │   ├── idna9.0.0.go
│   │   │   │   ├── idna9.0.0_test.go
│   │   │   │   ├── idna_test.go
│   │   │   │   ├── punycode.go
│   │   │   │   ├── punycode_test.go
│   │   │   │   ├── tables10.0.0.go
│   │   │   │   ├── tables11.0.0.go
│   │   │   │   ├── tables12.0.0.go
│   │   │   │   ├── tables9.0.0.go
│   │   │   │   ├── trie.go
│   │   │   │   └── trieval.go
│   │   │   ├── README
│   │   │   └── unicode
│   │   │       ├── doc.go
│   │   │       ├── gen.go
│   │   │       └── unicode_test.go
│   │   ├── format
│   │   │   ├── format.go
│   │   │   ├── parser.go
│   │   │   └── parser_test.go
│   │   ├── gen
│   │   │   ├── bitfield
│   │   │   │   ├── bitfield.go
│   │   │   │   ├── bitfield_test.go
│   │   │   │   ├── gen1_test.go
│   │   │   │   └── gen2_test.go
│   │   │   ├── code.go
│   │   │   └── gen.go
│   │   ├── internal.go
│   │   ├── internal_test.go
│   │   ├── language
│   │   │   ├── common.go
│   │   │   ├── compact
│   │   │   │   ├── compact.go
│   │   │   │   ├── gen.go
│   │   │   │   ├── gen_index.go
│   │   │   │   ├── gen_parents.go
│   │   │   │   ├── gen_test.go
│   │   │   │   ├── language.go
│   │   │   │   ├── language_test.go
│   │   │   │   ├── parents.go
│   │   │   │   ├── parse_test.go
│   │   │   │   ├── tables.go
│   │   │   │   └── tags.go
│   │   │   ├── compact.go
│   │   │   ├── compose.go
│   │   │   ├── compose_test.go
│   │   │   ├── coverage.go
│   │   │   ├── gen_common.go
│   │   │   ├── gen.go
│   │   │   ├── language.go
│   │   │   ├── language_test.go
│   │   │   ├── lookup.go
│   │   │   ├── lookup_test.go
│   │   │   ├── match.go
│   │   │   ├── match_test.go
│   │   │   ├── parse.go
│   │   │   ├── parse_test.go
│   │   │   ├── tables.go
│   │   │   └── tags.go
│   │   ├── match.go
│   │   ├── match_test.go
│   │   ├── number
│   │   │   ├── common.go
│   │   │   ├── decimal.go
│   │   │   ├── decimal_test.go
│   │   │   ├── format.go
│   │   │   ├── format_test.go
│   │   │   ├── gen_common.go
│   │   │   ├── gen.go
│   │   │   ├── number.go
│   │   │   ├── number_test.go
│   │   │   ├── pattern.go
│   │   │   ├── pattern_test.go
│   │   │   ├── roundingmode_string.go
│   │   │   ├── tables.go
│   │   │   └── tables_test.go
│   │   ├── stringset
│   │   │   ├── set.go
│   │   │   └── set_test.go
│   │   ├── tag
│   │   │   ├── tag.go
│   │   │   └── tag_test.go
│   │   ├── testtext
│   │   │   ├── codesize.go
│   │   │   ├── flag.go
│   │   │   ├── gccgo.go
│   │   │   ├── gc.go
│   │   │   ├── go1_6.go
│   │   │   ├── go1_7.go
│   │   │   └── text.go
│   │   ├── triegen
│   │   │   ├── compact.go
│   │   │   ├── data_test.go
│   │   │   ├── example_compact_test.go
│   │   │   ├── example_test.go
│   │   │   ├── gen_test.go
│   │   │   ├── print.go
│   │   │   └── triegen.go
│   │   ├── ucd
│   │   │   ├── example_test.go
│   │   │   ├── ucd.go
│   │   │   └── ucd_test.go
│   │   └── utf8internal
│   │       └── utf8internal.go
│   ├── language
│   │   ├── coverage.go
│   │   ├── coverage_test.go
│   │   ├── display
│   │   │   ├── dict.go
│   │   │   ├── dict_test.go
│   │   │   ├── display.go
│   │   │   ├── display_test.go
│   │   │   ├── examples_test.go
│   │   │   ├── lookup.go
│   │   │   ├── maketables.go
│   │   │   └── tables.go
│   │   ├── doc.go
│   │   ├── examples_test.go
│   │   ├── gen.go
│   │   ├── go1_1.go
│   │   ├── go1_2.go
│   │   ├── httpexample_test.go
│   │   ├── language.go
│   │   ├── language_test.go
│   │   ├── lookup_test.go
│   │   ├── match.go
│   │   ├── match_test.go
│   │   ├── parse.go
│   │   ├── parse_test.go
│   │   ├── tables.go
│   │   ├── tags.go
│   │   └── testdata
│   │       ├── CLDRLocaleMatcherTest.txt
│   │       └── GoLocaleMatcherTest.txt
│   ├── LICENSE
│   ├── message
│   │   ├── catalog
│   │   │   ├── catalog.go
│   │   │   ├── catalog_test.go
│   │   │   ├── dict.go
│   │   │   ├── go19.go
│   │   │   └── gopre19.go
│   │   ├── catalog.go
│   │   ├── catalog_test.go
│   │   ├── doc.go
│   │   ├── examples_test.go
│   │   ├── fmt_test.go
│   │   ├── format.go
│   │   ├── message.go
│   │   ├── message_test.go
│   │   ├── pipeline
│   │   │   ├── extract.go
│   │   │   ├── generate.go
│   │   │   ├── go19_test.go
│   │   │   ├── message.go
│   │   │   ├── pipeline.go
│   │   │   ├── pipeline_test.go
│   │   │   ├── rewrite.go
│   │   │   └── testdata
│   │   │       ├── ssa
│   │   │       │   ├── catalog_gen.go
│   │   │       │   ├── extracted.gotext.json
│   │   │       │   └── ssa.go
│   │   │       └── test1
│   │   │           ├── catalog_gen.go
│   │   │           ├── catalog_gen.go.want
│   │   │           ├── catalog_test.go
│   │   │           ├── extracted.gotext.json
│   │   │           ├── extracted.gotext.json.want
│   │   │           ├── locales
│   │   │           │   ├── de
│   │   │           │   │   ├── messages.gotext.json
│   │   │           │   │   ├── out.gotext.json
│   │   │           │   │   └── out.gotext.json.want
│   │   │           │   ├── en-US
│   │   │           │   │   ├── messages.gotext.json
│   │   │           │   │   ├── out.gotext.json
│   │   │           │   │   └── out.gotext.json.want
│   │   │           │   └── zh
│   │   │           │       ├── messages.gotext.json
│   │   │           │       ├── out.gotext.json
│   │   │           │       └── out.gotext.json.want
│   │   │           └── test1.go
│   │   └── print.go
│   ├── number
│   │   ├── doc.go
│   │   ├── examples_test.go
│   │   ├── format.go
│   │   ├── format_test.go
│   │   ├── number.go
│   │   ├── number_test.go
│   │   └── option.go
│   ├── PATENTS
│   ├── README.md
│   ├── runes
│   │   ├── cond.go
│   │   ├── cond_test.go
│   │   ├── example_test.go
│   │   ├── runes.go
│   │   └── runes_test.go
│   ├── search
│   │   ├── index.go
│   │   ├── pattern.go
│   │   ├── pattern_test.go
│   │   ├── search.go
│   │   └── tables.go
│   ├── secure
│   │   ├── bidirule
│   │   │   ├── bench_test.go
│   │   │   ├── bidirule10.0.0.go
│   │   │   ├── bidirule10.0.0_test.go
│   │   │   ├── bidirule9.0.0.go
│   │   │   ├── bidirule9.0.0_test.go
│   │   │   ├── bidirule.go
│   │   │   └── bidirule_test.go
│   │   ├── doc.go
│   │   └── precis
│   │       ├── benchmark_test.go
│   │       ├── class.go
│   │       ├── class_test.go
│   │       ├── context.go
│   │       ├── doc.go
│   │       ├── enforce10.0.0_test.go
│   │       ├── enforce9.0.0_test.go
│   │       ├── enforce_test.go
│   │       ├── gen.go
│   │       ├── gen_trieval.go
│   │       ├── nickname.go
│   │       ├── options.go
│   │       ├── profile.go
│   │       ├── profiles.go
│   │       ├── profile_test.go
│   │       ├── tables10.0.0.go
│   │       ├── tables11.0.0.go
│   │       ├── tables12.0.0.go
│   │       ├── tables9.0.0.go
│   │       ├── tables_test.go
│   │       ├── transformer.go
│   │       └── trieval.go
│   ├── transform
│   │   ├── examples_test.go
│   │   ├── transform.go
│   │   └── transform_test.go
│   ├── unicode
│   │   ├── bidi
│   │   │   ├── bidi.go
│   │   │   ├── bracket.go
│   │   │   ├── core.go
│   │   │   ├── core_test.go
│   │   │   ├── gen.go
│   │   │   ├── gen_ranges.go
│   │   │   ├── gen_trieval.go
│   │   │   ├── prop.go
│   │   │   ├── ranges_test.go
│   │   │   ├── tables10.0.0.go
│   │   │   ├── tables11.0.0.go
│   │   │   ├── tables12.0.0.go
│   │   │   ├── tables9.0.0.go
│   │   │   ├── tables_test.go
│   │   │   └── trieval.go
│   │   ├── cldr
│   │   │   ├── base.go
│   │   │   ├── cldr.go
│   │   │   ├── cldr_test.go
│   │   │   ├── collate.go
│   │   │   ├── collate_test.go
│   │   │   ├── data_test.go
│   │   │   ├── decode.go
│   │   │   ├── examples_test.go
│   │   │   ├── makexml.go
│   │   │   ├── resolve.go
│   │   │   ├── resolve_test.go
│   │   │   ├── slice.go
│   │   │   ├── slice_test.go
│   │   │   └── xml.go
│   │   ├── doc.go
│   │   ├── norm
│   │   │   ├── composition.go
│   │   │   ├── composition_test.go
│   │   │   ├── data10.0.0_test.go
│   │   │   ├── data11.0.0_test.go
│   │   │   ├── data12.0.0_test.go
│   │   │   ├── data9.0.0_test.go
│   │   │   ├── example_iter_test.go
│   │   │   ├── example_test.go
│   │   │   ├── forminfo.go
│   │   │   ├── forminfo_test.go
│   │   │   ├── input.go
│   │   │   ├── iter.go
│   │   │   ├── iter_test.go
│   │   │   ├── maketables.go
│   │   │   ├── normalize.go
│   │   │   ├── normalize_test.go
│   │   │   ├── readwriter.go
│   │   │   ├── readwriter_test.go
│   │   │   ├── tables10.0.0.go
│   │   │   ├── tables11.0.0.go
│   │   │   ├── tables12.0.0.go
│   │   │   ├── tables9.0.0.go
│   │   │   ├── transform.go
│   │   │   ├── transform_test.go
│   │   │   ├── triegen.go
│   │   │   ├── trie.go
│   │   │   └── ucd_test.go
│   │   ├── rangetable
│   │   │   ├── gen.go
│   │   │   ├── merge.go
│   │   │   ├── merge_test.go
│   │   │   ├── rangetable.go
│   │   │   ├── rangetable_test.go
│   │   │   ├── tables10.0.0.go
│   │   │   ├── tables11.0.0.go
│   │   │   ├── tables12.0.0.go
│   │   │   └── tables9.0.0.go
│   │   └── runenames
│   │       ├── example_test.go
│   │       ├── gen.go
│   │       ├── runenames.go
│   │       ├── runenames_test.go
│   │       ├── tables10.0.0.go
│   │       ├── tables11.0.0.go
│   │       ├── tables12.0.0.go
│   │       └── tables9.0.0.go
│   └── width
│       ├── common_test.go
│       ├── example_test.go
│       ├── gen_common.go
│       ├── gen.go
│       ├── gen_trieval.go
│       ├── kind_string.go
│       ├── runes_test.go
│       ├── tables10.0.0.go
│       ├── tables11.0.0.go
│       ├── tables12.0.0.go
│       ├── tables9.0.0.go
│       ├── tables_test.go
│       ├── transform.go
│       ├── transform_test.go
│       ├── trieval.go
│       └── width.go
└── tools
    ├── AUTHORS
    ├── benchmark
    │   └── parse
    │       ├── parse.go
    │       └── parse_test.go
    ├── blog
    │   ├── atom
    │   │   └── atom.go
    │   ├── blog.go
    │   └── blog_test.go
    ├── cmd
    │   ├── auth
    │   │   ├── authtest
    │   │   │   └── authtest.go
    │   │   ├── cookieauth
    │   │   │   └── cookieauth.go
    │   │   ├── gitauth
    │   │   │   └── gitauth.go
    │   │   └── netrcauth
    │   │       └── netrcauth.go
    │   ├── benchcmp
    │   │   ├── benchcmp.go
    │   │   ├── benchcmp_test.go
    │   │   ├── compare.go
    │   │   ├── compare_test.go
    │   │   └── doc.go
    │   ├── bundle
    │   │   ├── main.go
    │   │   ├── main_test.go
    │   │   └── testdata
    │   │       ├── out.golden
    │   │       └── src
    │   │           ├── domain.name
    │   │           │   └── importdecl
    │   │           │       └── p.go
    │   │           └── initial
    │   │               ├── a.go
    │   │               ├── b.go
    │   │               └── c.go
    │   ├── callgraph
    │   │   ├── main.go
    │   │   ├── main_test.go
    │   │   └── testdata
    │   │       └── src
    │   │           └── pkg
    │   │               ├── pkg.go
    │   │               └── pkg_test.go
    │   ├── compilebench
    │   │   └── main.go
    │   ├── cover
    │   │   ├── cover.go
    │   │   ├── cover_test.go
    │   │   ├── doc.go
    │   │   ├── func.go
    │   │   ├── html.go
    │   │   ├── README
    │   │   └── testdata
    │   │       ├── main.go
    │   │       └── test.go
    │   ├── digraph
    │   │   ├── digraph.go
    │   │   └── digraph_test.go
    │   ├── eg
    │   │   └── eg.go
    │   ├── fiximports
    │   │   ├── main.go
    │   │   ├── main_test.go
    │   │   └── testdata
    │   │       └── src
    │   │           ├── fruit.io
    │   │           │   ├── banana
    │   │           │   │   └── banana.go
    │   │           │   ├── orange
    │   │           │   │   └── orange.go
    │   │           │   └── pear
    │   │           │       └── pear.go
    │   │           ├── new.com
    │   │           │   └── one
    │   │           │       └── one.go
    │   │           ├── old.com
    │   │           │   ├── bad
    │   │           │   │   └── bad.go
    │   │           │   └── one
    │   │           │       └── one.go
    │   │           └── titanic.biz
    │   │               ├── bar
    │   │               │   └── bar.go
    │   │               └── foo
    │   │                   └── foo.go
    │   ├── getgo
    │   │   ├── Dockerfile
    │   │   ├── download.go
    │   │   ├── download_test.go
    │   │   ├── LICENSE
    │   │   ├── main.go
    │   │   ├── main_test.go
    │   │   ├── make.bash
    │   │   ├── path.go
    │   │   ├── path_test.go
    │   │   ├── README.md
    │   │   ├── server
    │   │   │   ├── app.yaml
    │   │   │   ├── main.go
    │   │   │   └── README.md
    │   │   ├── steps.go
    │   │   ├── system.go
    │   │   ├── system_unix.go
    │   │   ├── system_windows.go
    │   │   └── upload.bash
    │   ├── go-contrib-init
    │   │   ├── contrib.go
    │   │   └── contrib_test.go
    │   ├── godex
    │   │   ├── doc.go
    │   │   ├── gccgo.go
    │   │   ├── gc.go
    │   │   ├── godex.go
    │   │   ├── isAlias18.go
    │   │   ├── isAlias19.go
    │   │   ├── print.go
    │   │   ├── source.go
    │   │   └── writetype.go
    │   ├── godoc
    │   │   ├── blog.go
    │   │   ├── codewalk.go
    │   │   ├── dl.go
    │   │   ├── doc.go
    │   │   ├── godoc_test.go
    │   │   ├── goroot.go
    │   │   ├── handlers.go
    │   │   ├── index.go
    │   │   ├── main.go
    │   │   └── play.go
    │   ├── goimports
    │   │   ├── doc.go
    │   │   ├── goimports_gc.go
    │   │   ├── goimports.go
    │   │   └── goimports_not_gc.go
    │   ├── gomvpkg
    │   │   └── main.go
    │   ├── gopls
    │   │   ├── integration
    │   │   │   └── vscode
    │   │   │       ├── package.json
    │   │   │       ├── package-lock.json
    │   │   │       ├── README.md
    │   │   │       ├── src
    │   │   │       │   └── extension.ts
    │   │   │       ├── tsconfig.json
    │   │   │       └── tslint.json
    │   │   └── main.go
    │   ├── gorename
    │   │   ├── cgo_test.go
    │   │   ├── gorename_test.go
    │   │   └── main.go
    │   ├── gotype
    │   │   ├── gotype.go
    │   │   ├── sizesFor18.go
    │   │   └── sizesFor19.go
    │   ├── goyacc
    │   │   ├── doc.go
    │   │   ├── testdata
    │   │   │   └── expr
    │   │   │       ├── expr.y
    │   │   │       ├── main.go
    │   │   │       └── README
    │   │   └── yacc.go
    │   ├── guru
    │   │   ├── callees.go
    │   │   ├── callers.go
    │   │   ├── callstack.go
    │   │   ├── definition.go
    │   │   ├── describe.go
    │   │   ├── freevars.go
    │   │   ├── guru.go
    │   │   ├── guru_test.go
    │   │   ├── implements.go
    │   │   ├── isAlias18.go
    │   │   ├── isAlias19.go
    │   │   ├── main.go
    │   │   ├── peers.go
    │   │   ├── pointsto.go
    │   │   ├── pos.go
    │   │   ├── referrers.go
    │   │   ├── serial
    │   │   │   └── serial.go
    │   │   ├── testdata
    │   │   │   └── src
    │   │   │       ├── alias
    │   │   │       │   ├── alias.go
    │   │   │       │   └── alias.golden
    │   │   │       ├── calls
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── calls-json
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── definition-json
    │   │   │       │   ├── main.go
    │   │   │       │   ├── main.golden
    │   │   │       │   └── type.go
    │   │   │       ├── describe
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── describe-json
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── freevars
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── implements
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── implements-json
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── implements-methods
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── implements-methods-json
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── imports
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── lib
    │   │   │       │   ├── lib.go
    │   │   │       │   └── sublib
    │   │   │       │       └── sublib.go
    │   │   │       ├── main
    │   │   │       │   └── multi.go
    │   │   │       ├── peers
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── peers-json
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── pointsto
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── pointsto-json
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── README.txt
    │   │   │       ├── referrers
    │   │   │       │   ├── ext_test.go
    │   │   │       │   ├── int_test.go
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── referrers-json
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── reflection
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── softerrs
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── what
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       ├── what-json
    │   │   │       │   ├── main.go
    │   │   │       │   └── main.golden
    │   │   │       └── whicherrs
    │   │   │           ├── main.go
    │   │   │           └── main.golden
    │   │   ├── unit_test.go
    │   │   ├── what.go
    │   │   └── whicherrs.go
    │   ├── html2article
    │   │   └── conv.go
    │   ├── present
    │   │   ├── dir.go
    │   │   ├── doc.go
    │   │   ├── main.go
    │   │   ├── play.go
    │   │   ├── static
    │   │   │   ├── article.css
    │   │   │   ├── dir.css
    │   │   │   ├── dir.js
    │   │   │   ├── favicon.ico
    │   │   │   ├── jquery-ui.js
    │   │   │   ├── notes.css
    │   │   │   ├── notes.js
    │   │   │   ├── slides.js
    │   │   │   └── styles.css
    │   │   └── templates
    │   │       ├── action.tmpl
    │   │       ├── article.tmpl
    │   │       ├── dir.tmpl
    │   │       └── slides.tmpl
    │   ├── splitdwarf
    │   │   ├── internal
    │   │   │   └── macho
    │   │   │       ├── fat.go
    │   │   │       ├── file.go
    │   │   │       ├── file_test.go
    │   │   │       ├── macho.go
    │   │   │       ├── reloctype.go
    │   │   │       ├── reloctype_string.go
    │   │   │       └── testdata
    │   │   │           ├── clang-386-darwin-exec-with-rpath
    │   │   │           ├── clang-386-darwin.obj
    │   │   │           ├── clang-amd64-darwin-exec-with-rpath
    │   │   │           ├── clang-amd64-darwin.obj
    │   │   │           ├── fat-gcc-386-amd64-darwin-exec
    │   │   │           ├── gcc-386-darwin-exec
    │   │   │           ├── gcc-amd64-darwin-exec
    │   │   │           ├── gcc-amd64-darwin-exec-debug
    │   │   │           └── hello.c
    │   │   └── splitdwarf.go
    │   ├── ssadump
    │   │   └── main.go
    │   ├── stress
    │   │   └── stress.go
    │   ├── stringer
    │   │   ├── endtoend_test.go
    │   │   ├── golden_test.go
    │   │   ├── stringer.go
    │   │   ├── testdata
    │   │   │   ├── cgo.go
    │   │   │   ├── conv.go
    │   │   │   ├── day.go
    │   │   │   ├── gap.go
    │   │   │   ├── number.go
    │   │   │   ├── num.go
    │   │   │   ├── prime.go
    │   │   │   ├── tag_main.go
    │   │   │   ├── tag_tag.go
    │   │   │   ├── unum2.go
    │   │   │   ├── unum.go
    │   │   │   └── vary_day.go
    │   │   └── util_test.go
    │   └── toolstash
    │       ├── buildall
    │       ├── cmp.go
    │       └── main.go
    ├── codereview.cfg
    ├── container
    │   └── intsets
    │       ├── popcnt_amd64.go
    │       ├── popcnt_amd64.s
    │       ├── popcnt_gccgo_c.c
    │       ├── popcnt_gccgo.go
    │       ├── popcnt_generic.go
    │       ├── sparse.go
    │       ├── sparse_test.go
    │       ├── util.go
    │       └── util_test.go
    ├── CONTRIBUTING.md
    ├── CONTRIBUTORS
    ├── cover
    │   ├── profile.go
    │   └── profile_test.go
    ├── go
    │   ├── analysis
    │   │   ├── analysis.go
    │   │   ├── analysistest
    │   │   │   ├── analysistest.go
    │   │   │   └── analysistest_test.go
    │   │   ├── diagnostic.go
    │   │   ├── doc
    │   │   │   └── suggested_fixes.md
    │   │   ├── doc.go
    │   │   ├── internal
    │   │   │   ├── analysisflags
    │   │   │   │   ├── flags.go
    │   │   │   │   ├── flags_test.go
    │   │   │   │   └── help.go
    │   │   │   ├── checker
    │   │   │   │   ├── checker.go
    │   │   │   │   └── checker_test.go
    │   │   │   └── facts
    │   │   │       ├── facts.go
    │   │   │       ├── facts_test.go
    │   │   │       └── imports.go
    │   │   ├── multichecker
    │   │   │   ├── multichecker.go
    │   │   │   └── multichecker_test.go
    │   │   ├── passes
    │   │   │   ├── asmdecl
    │   │   │   │   ├── asmdecl.go
    │   │   │   │   ├── asmdecl_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               ├── asm1.s
    │   │   │   │               ├── asm2.s
    │   │   │   │               ├── asm3.s
    │   │   │   │               ├── asm4.s
    │   │   │   │               ├── asm5.s
    │   │   │   │               ├── asm6.s
    │   │   │   │               ├── asm7.s
    │   │   │   │               ├── asm8.s
    │   │   │   │               ├── asm9.s
    │   │   │   │               └── asm.go
    │   │   │   ├── assign
    │   │   │   │   ├── assign.go
    │   │   │   │   ├── assign_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── a.go
    │   │   │   ├── atomic
    │   │   │   │   ├── atomic.go
    │   │   │   │   ├── atomic_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── a.go
    │   │   │   ├── atomicalign
    │   │   │   │   ├── atomicalign.go
    │   │   │   │   ├── atomicalign_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           ├── a
    │   │   │   │           │   ├── a.go
    │   │   │   │           │   └── stub.go
    │   │   │   │           └── b
    │   │   │   │               ├── b.go
    │   │   │   │               └── stub.go
    │   │   │   ├── bools
    │   │   │   │   ├── bools.go
    │   │   │   │   ├── bools_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── a.go
    │   │   │   ├── buildssa
    │   │   │   │   ├── buildssa.go
    │   │   │   │   ├── buildssa_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── a.go
    │   │   │   ├── buildtag
    │   │   │   │   ├── buildtag.go
    │   │   │   │   ├── buildtag_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── buildtag.go
    │   │   │   ├── cgocall
    │   │   │   │   ├── cgocall.go
    │   │   │   │   ├── cgocall_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           ├── a
    │   │   │   │           │   ├── cgo3.go
    │   │   │   │           │   └── cgo.go
    │   │   │   │           ├── b
    │   │   │   │           │   └── b.go
    │   │   │   │           └── c
    │   │   │   │               └── c.go
    │   │   │   ├── composite
    │   │   │   │   ├── composite.go
    │   │   │   │   ├── composite_test.go
    │   │   │   │   ├── testdata
    │   │   │   │   │   └── src
    │   │   │   │   │       └── a
    │   │   │   │   │           └── a.go
    │   │   │   │   └── whitelist.go
    │   │   │   ├── copylock
    │   │   │   │   ├── copylock.go
    │   │   │   │   ├── copylock_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               ├── copylock_func.go
    │   │   │   │               ├── copylock.go
    │   │   │   │               └── copylock_range.go
    │   │   │   ├── ctrlflow
    │   │   │   │   ├── ctrlflow.go
    │   │   │   │   ├── ctrlflow_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           ├── a
    │   │   │   │           │   └── a.go
    │   │   │   │           └── lib
    │   │   │   │               └── lib.go
    │   │   │   ├── deepequalerrors
    │   │   │   │   ├── deepequalerrors.go
    │   │   │   │   ├── deepequalerrors_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── a.go
    │   │   │   ├── errorsas
    │   │   │   │   ├── errorsas.go
    │   │   │   │   ├── errorsas_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── a.go
    │   │   │   ├── findcall
    │   │   │   │   ├── cmd
    │   │   │   │   │   └── findcall
    │   │   │   │   │       └── main.go
    │   │   │   │   ├── findcall.go
    │   │   │   │   ├── findcall_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── a.go
    │   │   │   ├── httpresponse
    │   │   │   │   ├── httpresponse.go
    │   │   │   │   ├── httpresponse_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── a.go
    │   │   │   ├── inspect
    │   │   │   │   └── inspect.go
    │   │   │   ├── internal
    │   │   │   │   └── analysisutil
    │   │   │   │       └── util.go
    │   │   │   ├── loopclosure
    │   │   │   │   ├── loopclosure.go
    │   │   │   │   ├── loopclosure_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── a.go
    │   │   │   ├── lostcancel
    │   │   │   │   ├── cmd
    │   │   │   │   │   └── lostcancel
    │   │   │   │   │       └── main.go
    │   │   │   │   ├── lostcancel.go
    │   │   │   │   ├── lostcancel_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           ├── a
    │   │   │   │           │   └── a.go
    │   │   │   │           └── b
    │   │   │   │               └── b.go
    │   │   │   ├── nilfunc
    │   │   │   │   ├── nilfunc.go
    │   │   │   │   ├── nilfunc_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── a.go
    │   │   │   ├── nilness
    │   │   │   │   ├── cmd
    │   │   │   │   │   └── nilness
    │   │   │   │   │       └── main.go
    │   │   │   │   ├── nilness.go
    │   │   │   │   ├── nilness_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── a.go
    │   │   │   ├── pkgfact
    │   │   │   │   ├── pkgfact.go
    │   │   │   │   ├── pkgfact_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           ├── a
    │   │   │   │           │   └── a.go
    │   │   │   │           ├── b
    │   │   │   │           │   └── b.go
    │   │   │   │           └── c
    │   │   │   │               └── c.go
    │   │   │   ├── printf
    │   │   │   │   ├── printf.go
    │   │   │   │   ├── printf_test.go
    │   │   │   │   ├── testdata
    │   │   │   │   │   └── src
    │   │   │   │   │       ├── a
    │   │   │   │   │       │   └── a.go
    │   │   │   │   │       ├── b
    │   │   │   │   │       │   └── b.go
    │   │   │   │   │       └── nofmt
    │   │   │   │   │           └── nofmt.go
    │   │   │   │   └── types.go
    │   │   │   ├── README
    │   │   │   ├── shadow
    │   │   │   │   ├── cmd
    │   │   │   │   │   └── shadow
    │   │   │   │   │       └── main.go
    │   │   │   │   ├── shadow.go
    │   │   │   │   ├── shadow_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── a.go
    │   │   │   ├── shift
    │   │   │   │   ├── dead.go
    │   │   │   │   ├── shift.go
    │   │   │   │   ├── shift_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── a.go
    │   │   │   ├── sortslice
    │   │   │   │   ├── analyzer.go
    │   │   │   │   ├── analyzer_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── a.go
    │   │   │   ├── stdmethods
    │   │   │   │   ├── stdmethods.go
    │   │   │   │   ├── stdmethods_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               └── a.go
    │   │   │   ├── structtag
    │   │   │   │   ├── structtag.go
    │   │   │   │   ├── structtag_test.go
    │   │   │   │   └── testdata
    │   │   │   │       └── src
    │   │   │   │           └── a
    │   │   │   │               ├── a.go
    │   │   │   │               └── b
    │   │   │   │                   └── b.go
    │   │   │   ├── tests
    │   │   │   │   ├── testdata
    │   │   │   │   │   └── src
    │   │   │   │   │       ├── a
    │   │   │   │   │       │   ├── a.go
    │   │   │   │   │       │   ├── a_test.go
    │   │   │   │   │       │   └── ax_test.go
    │   │   │   │   │       ├── b
    │   │   │   │   │       │   └── b.go
    │   │   │   │   │       ├── b_x_test
    │   │   │   │   │       │   └── b_test.go
    │   │   │   │   │       └── divergent
    │   │   │   │   │           ├── buf.go
    │   │   │   │   │           └── buf_test.go
    │   │   │   │   ├── tests.go
    │   │   │   │   └── tests_test.go
    │   │   │   ├── unmarshal
    │   │   │   │   ├── cmd
    │   │   │   │   │   └── unmarshal
    │   │   │   │   │       └── main.go
    │   │   │   │   ├── testdata
    │   │   │   │   │   └── src
    │   │   │   │   │       └── a
    │   │   │   │   │           └── a.go
    │   │   │   │   ├── unmarshal.go
    │   │   │   │   └── unmarshal_test.go
    │   │   │   ├── unreachable
    │   │   │   │   ├── testdata
    │   │   │   │   │   └── src
    │   │   │   │   │       └── a
    │   │   │   │   │           └── a.go
    │   │   │   │   ├── unreachable.go
    │   │   │   │   └── unreachable_test.go
    │   │   │   ├── unsafeptr
    │   │   │   │   ├── testdata
    │   │   │   │   │   └── src
    │   │   │   │   │       └── a
    │   │   │   │   │           └── a.go
    │   │   │   │   ├── unsafeptr.go
    │   │   │   │   └── unsafeptr_test.go
    │   │   │   └── unusedresult
    │   │   │       ├── testdata
    │   │   │       │   └── src
    │   │   │       │       └── a
    │   │   │       │           └── a.go
    │   │   │       ├── unusedresult.go
    │   │   │       └── unusedresult_test.go
    │   │   ├── singlechecker
    │   │   │   └── singlechecker.go
    │   │   ├── unitchecker
    │   │   │   ├── main.go
    │   │   │   ├── unitchecker112.go
    │   │   │   ├── unitchecker.go
    │   │   │   └── unitchecker_test.go
    │   │   └── validate.go
    │   ├── ast
    │   │   ├── astutil
    │   │   │   ├── enclosing.go
    │   │   │   ├── enclosing_test.go
    │   │   │   ├── imports.go
    │   │   │   ├── imports_test.go
    │   │   │   ├── rewrite.go
    │   │   │   ├── rewrite_test.go
    │   │   │   └── util.go
    │   │   └── inspector
    │   │       ├── inspector.go
    │   │       ├── inspector_test.go
    │   │       └── typeof.go
    │   ├── buildutil
    │   │   ├── allpackages.go
    │   │   ├── allpackages_test.go
    │   │   ├── fakecontext.go
    │   │   ├── overlay.go
    │   │   ├── overlay_test.go
    │   │   ├── tags.go
    │   │   ├── tags_test.go
    │   │   ├── util.go
    │   │   ├── util_test.go
    │   │   └── util_windows_test.go
    │   ├── callgraph
    │   │   ├── callgraph.go
    │   │   ├── cha
    │   │   │   ├── cha.go
    │   │   │   ├── cha_test.go
    │   │   │   └── testdata
    │   │   │       ├── func.go
    │   │   │       ├── iface.go
    │   │   │       ├── issue23925.go
    │   │   │       └── recv.go
    │   │   ├── rta
    │   │   │   ├── rta.go
    │   │   │   ├── rta_test.go
    │   │   │   └── testdata
    │   │   │       ├── func.go
    │   │   │       ├── iface.go
    │   │   │       └── rtype.go
    │   │   ├── static
    │   │   │   ├── static.go
    │   │   │   └── static_test.go
    │   │   └── util.go
    │   ├── cfg
    │   │   ├── builder.go
    │   │   ├── cfg.go
    │   │   └── cfg_test.go
    │   ├── expect
    │   │   ├── expect.go
    │   │   ├── expect_test.go
    │   │   ├── extract.go
    │   │   └── testdata
    │   │       └── test.go
    │   ├── gccgoexportdata
    │   │   ├── gccgoexportdata.go
    │   │   ├── gccgoexportdata_test.go
    │   │   └── testdata
    │   │       ├── errors.gox
    │   │       ├── long.a
    │   │       └── short.a
    │   ├── gcexportdata
    │   │   ├── example_test.go
    │   │   ├── gcexportdata.go
    │   │   ├── gcexportdata_test.go
    │   │   ├── importer.go
    │   │   ├── main.go
    │   │   └── testdata
    │   │       └── errors-ae16.a
    │   ├── internal
    │   │   ├── cgo
    │   │   │   ├── cgo.go
    │   │   │   └── cgo_pkgconfig.go
    │   │   ├── gccgoimporter
    │   │   │   ├── ar.go
    │   │   │   ├── backdoor.go
    │   │   │   ├── gccgoinstallation.go
    │   │   │   ├── gccgoinstallation_test.go
    │   │   │   ├── importer.go
    │   │   │   ├── importer_test.go
    │   │   │   ├── newInterface10.go
    │   │   │   ├── newInterface11.go
    │   │   │   ├── parser.go
    │   │   │   ├── parser_test.go
    │   │   │   ├── testdata
    │   │   │   │   ├── aliases.go
    │   │   │   │   ├── aliases.gox
    │   │   │   │   ├── complexnums.go
    │   │   │   │   ├── complexnums.gox
    │   │   │   │   ├── conversions.go
    │   │   │   │   ├── conversions.gox
    │   │   │   │   ├── escapeinfo.go
    │   │   │   │   ├── escapeinfo.gox
    │   │   │   │   ├── imports.go
    │   │   │   │   ├── imports.gox
    │   │   │   │   ├── issue27856.go
    │   │   │   │   ├── issue27856.gox
    │   │   │   │   ├── issue29198.go
    │   │   │   │   ├── issue29198.gox
    │   │   │   │   ├── issue30628.go
    │   │   │   │   ├── issue30628.gox
    │   │   │   │   ├── issue31540.go
    │   │   │   │   ├── issue31540.gox
    │   │   │   │   ├── issue34182.go
    │   │   │   │   ├── issue34182.gox
    │   │   │   │   ├── libimportsar.a
    │   │   │   │   ├── nointerface.go
    │   │   │   │   ├── nointerface.gox
    │   │   │   │   ├── pointer.go
    │   │   │   │   ├── pointer.gox
    │   │   │   │   ├── time.gox
    │   │   │   │   ├── unicode.gox
    │   │   │   │   └── v1reflect.gox
    │   │   │   └── testenv_test.go
    │   │   ├── gcimporter
    │   │   │   ├── bexport.go
    │   │   │   ├── bexport_test.go
    │   │   │   ├── bimport.go
    │   │   │   ├── exportdata.go
    │   │   │   ├── gcimporter11_test.go
    │   │   │   ├── gcimporter.go
    │   │   │   ├── gcimporter_test.go
    │   │   │   ├── iexport.go
    │   │   │   ├── iexport_test.go
    │   │   │   ├── iimport.go
    │   │   │   ├── israce_test.go
    │   │   │   ├── newInterface10.go
    │   │   │   ├── newInterface11.go
    │   │   │   └── testdata
    │   │   │       ├── a.go
    │   │   │       ├── b.go
    │   │   │       ├── exports.go
    │   │   │       ├── issue15920.go
    │   │   │       ├── issue20046.go
    │   │   │       ├── issue25301.go
    │   │   │       ├── p.go
    │   │   │       └── versions
    │   │   │           ├── test.go
    │   │   │           ├── test_go1.11_0i.a
    │   │   │           ├── test_go1.11_6b.a
    │   │   │           ├── test_go1.11_999b.a
    │   │   │           ├── test_go1.11_999i.a
    │   │   │           ├── test_go1.7_0.a
    │   │   │           ├── test_go1.7_1.a
    │   │   │           ├── test_go1.8_4.a
    │   │   │           └── test_go1.8_5.a
    │   │   └── packagesdriver
    │   │       └── sizes.go
    │   ├── loader
    │   │   ├── doc.go
    │   │   ├── example_test.go
    │   │   ├── loader.go
    │   │   ├── loader_test.go
    │   │   ├── stdlib_test.go
    │   │   ├── testdata
    │   │   │   ├── a.go
    │   │   │   ├── badpkgdecl.go
    │   │   │   └── b.go
    │   │   └── util.go
    │   ├── packages
    │   │   ├── doc.go
    │   │   ├── example_test.go
    │   │   ├── external.go
    │   │   ├── golist.go
    │   │   ├── golist_overlay.go
    │   │   ├── gopackages
    │   │   │   └── main.go
    │   │   ├── packages110_test.go
    │   │   ├── packagescgo_test.go
    │   │   ├── packages.go
    │   │   ├── packagestest
    │   │   │   ├── expect.go
    │   │   │   ├── expect_test.go
    │   │   │   ├── export.go
    │   │   │   ├── export_test.go
    │   │   │   ├── gopath.go
    │   │   │   ├── gopath_test.go
    │   │   │   ├── modules_111.go
    │   │   │   ├── modules_112.go
    │   │   │   ├── modules_113.go
    │   │   │   ├── modules.go
    │   │   │   ├── modules_test.go
    │   │   │   └── testdata
    │   │   │       └── test.go
    │   │   ├── packages_test.go
    │   │   ├── stdlib_test.go
    │   │   ├── testdata
    │   │   │   ├── README
    │   │   │   └── TestName_ModulesDedup
    │   │   │       └── pkg
    │   │   │           └── mod
    │   │   │               ├── cache
    │   │   │               │   └── download
    │   │   │               │       └── github.com
    │   │   │               │           └── heschik
    │   │   │               │               └── tools-testrepo
    │   │   │               │                   ├── @v
    │   │   │               │                   │   ├── list
    │   │   │               │                   │   ├── v1.0.0.info
    │   │   │               │                   │   ├── v1.0.0.mod
    │   │   │               │                   │   ├── v1.0.0.zip
    │   │   │               │                   │   └── v1.0.0.ziphash
    │   │   │               │                   └── v2
    │   │   │               │                       └── @v
    │   │   │               │                           ├── list
    │   │   │               │                           ├── v2.0.1.info
    │   │   │               │                           ├── v2.0.1.mod
    │   │   │               │                           ├── v2.0.1.zip
    │   │   │               │                           ├── v2.0.1.ziphash
    │   │   │               │                           ├── v2.0.2.info
    │   │   │               │                           ├── v2.0.2.mod
    │   │   │               │                           ├── v2.0.2.zip
    │   │   │               │                           └── v2.0.2.ziphash
    │   │   │               └── github.com
    │   │   │                   └── heschik
    │   │   │                       ├── tools-testrepo
    │   │   │                       │   ├── v2@v2.0.1
    │   │   │                       │   │   ├── definitelynot_go.mod
    │   │   │                       │   │   └── pkg
    │   │   │                       │   │       └── pkg.go
    │   │   │                       │   └── v2@v2.0.2
    │   │   │                       │       ├── definitelynot_go.mod
    │   │   │                       │       └── pkg
    │   │   │                       │           └── pkg.go
    │   │   │                       └── tools-testrepo@v1.0.0
    │   │   │                           ├── definitelynot_go.mod
    │   │   │                           └── pkg
    │   │   │                               └── pkg.go
    │   │   └── visit.go
    │   ├── pointer
    │   │   ├── analysis.go
    │   │   ├── api.go
    │   │   ├── callgraph.go
    │   │   ├── constraint.go
    │   │   ├── doc.go
    │   │   ├── example_test.go
    │   │   ├── gen.go
    │   │   ├── hvn.go
    │   │   ├── intrinsics.go
    │   │   ├── labels.go
    │   │   ├── opt.go
    │   │   ├── pointer_test.go
    │   │   ├── print.go
    │   │   ├── query.go
    │   │   ├── query_test.go
    │   │   ├── reflect.go
    │   │   ├── solve.go
    │   │   ├── stdlib_test.go
    │   │   ├── testdata
    │   │   │   ├── another.go
    │   │   │   ├── arrayreflect.go
    │   │   │   ├── arrays.go
    │   │   │   ├── a_test.go
    │   │   │   ├── channels.go
    │   │   │   ├── chanreflect1.go
    │   │   │   ├── chanreflect.go
    │   │   │   ├── context.go
    │   │   │   ├── conv.go
    │   │   │   ├── extended.go
    │   │   │   ├── finalizer.go
    │   │   │   ├── flow.go
    │   │   │   ├── fmtexcerpt.go
    │   │   │   ├── func.go
    │   │   │   ├── funcreflect.go
    │   │   │   ├── hello.go
    │   │   │   ├── interfaces.go
    │   │   │   ├── issue9002.go
    │   │   │   ├── mapreflect.go
    │   │   │   ├── maps.go
    │   │   │   ├── panic.go
    │   │   │   ├── recur.go
    │   │   │   ├── reflect.go
    │   │   │   ├── rtti.go
    │   │   │   ├── structreflect.go
    │   │   │   ├── structs.go
    │   │   │   └── timer.go
    │   │   ├── TODO
    │   │   └── util.go
    │   ├── ssa
    │   │   ├── blockopt.go
    │   │   ├── builder.go
    │   │   ├── builder_test.go
    │   │   ├── const.go
    │   │   ├── create.go
    │   │   ├── doc.go
    │   │   ├── dom.go
    │   │   ├── emit.go
    │   │   ├── example_test.go
    │   │   ├── func.go
    │   │   ├── identical_17.go
    │   │   ├── identical.go
    │   │   ├── identical_test.go
    │   │   ├── interp
    │   │   │   ├── external.go
    │   │   │   ├── interp.go
    │   │   │   ├── interp_test.go
    │   │   │   ├── map.go
    │   │   │   ├── ops.go
    │   │   │   ├── reflect.go
    │   │   │   ├── testdata
    │   │   │   │   ├── boundmeth.go
    │   │   │   │   ├── complit.go
    │   │   │   │   ├── coverage.go
    │   │   │   │   ├── defer.go
    │   │   │   │   ├── fieldprom.go
    │   │   │   │   ├── ifaceconv.go
    │   │   │   │   ├── ifaceprom.go
    │   │   │   │   ├── initorder.go
    │   │   │   │   ├── methprom.go
    │   │   │   │   ├── mrvchain.go
    │   │   │   │   ├── range.go
    │   │   │   │   ├── recover.go
    │   │   │   │   ├── reflect.go
    │   │   │   │   ├── src
    │   │   │   │   │   ├── errors
    │   │   │   │   │   │   └── errors.go
    │   │   │   │   │   ├── fmt
    │   │   │   │   │   │   └── fmt.go
    │   │   │   │   │   ├── math
    │   │   │   │   │   │   └── math.go
    │   │   │   │   │   ├── os
    │   │   │   │   │   │   └── os.go
    │   │   │   │   │   ├── reflect
    │   │   │   │   │   │   └── reflect.go
    │   │   │   │   │   ├── runtime
    │   │   │   │   │   │   └── runtime.go
    │   │   │   │   │   ├── strings
    │   │   │   │   │   │   └── strings.go
    │   │   │   │   │   ├── time
    │   │   │   │   │   │   └── time.go
    │   │   │   │   │   ├── unicode
    │   │   │   │   │   │   └── utf8
    │   │   │   │   │   │       └── utf8.go
    │   │   │   │   │   └── unsafe
    │   │   │   │   │       └── unsafe.go
    │   │   │   │   └── static.go
    │   │   │   └── value.go
    │   │   ├── lift.go
    │   │   ├── lvalue.go
    │   │   ├── methods.go
    │   │   ├── mode.go
    │   │   ├── print.go
    │   │   ├── sanity.go
    │   │   ├── source.go
    │   │   ├── source_test.go
    │   │   ├── ssa.go
    │   │   ├── ssautil
    │   │   │   ├── load.go
    │   │   │   ├── load_test.go
    │   │   │   ├── switch.go
    │   │   │   ├── switch_test.go
    │   │   │   ├── testdata
    │   │   │   │   └── switches.go
    │   │   │   └── visit.go
    │   │   ├── stdlib_test.go
    │   │   ├── testdata
    │   │   │   ├── objlookup.go
    │   │   │   ├── structconv.go
    │   │   │   └── valueforexpr.go
    │   │   ├── testmain.go
    │   │   ├── testmain_test.go
    │   │   ├── util.go
    │   │   └── wrappers.go
    │   ├── types
    │   │   ├── objectpath
    │   │   │   ├── objectpath.go
    │   │   │   └── objectpath_test.go
    │   │   └── typeutil
    │   │       ├── callee.go
    │   │       ├── callee_test.go
    │   │       ├── example_test.go
    │   │       ├── imports.go
    │   │       ├── imports_test.go
    │   │       ├── map.go
    │   │       ├── map_test.go
    │   │       ├── methodsetcache.go
    │   │       ├── ui.go
    │   │       └── ui_test.go
    │   └── vcs
    │       ├── discovery.go
    │       ├── env.go
    │       ├── http.go
    │       ├── vcs.go
    │       └── vcs_test.go
    ├── godoc
    │   ├── analysis
    │   │   ├── analysis.go
    │   │   ├── callgraph.go
    │   │   ├── implements.go
    │   │   ├── json.go
    │   │   ├── peers.go
    │   │   ├── README
    │   │   └── typeinfo.go
    │   ├── corpus.go
    │   ├── dirtrees.go
    │   ├── dirtrees_test.go
    │   ├── format.go
    │   ├── godoc17_test.go
    │   ├── godoc.go
    │   ├── godoc_test.go
    │   ├── golangorgenv
    │   │   └── golangorgenv.go
    │   ├── index.go
    │   ├── index_test.go
    │   ├── linkify.go
    │   ├── meta.go
    │   ├── page.go
    │   ├── parser.go
    │   ├── pres.go
    │   ├── README.md
    │   ├── redirect
    │   │   ├── hash.go
    │   │   ├── redirect.go
    │   │   ├── redirect_test.go
    │   │   └── rietveld.go
    │   ├── search.go
    │   ├── server.go
    │   ├── server_test.go
    │   ├── snippet.go
    │   ├── spec.go
    │   ├── spec_test.go
    │   ├── spot.go
    │   ├── static
    │   │   ├── analysis
    │   │   │   ├── call3.png
    │   │   │   ├── call-eg.png
    │   │   │   ├── callers1.png
    │   │   │   ├── callers2.png
    │   │   │   ├── chan1.png
    │   │   │   ├── chan2a.png
    │   │   │   ├── chan2b.png
    │   │   │   ├── error1.png
    │   │   │   ├── help.html
    │   │   │   ├── ident-def.png
    │   │   │   ├── ident-field.png
    │   │   │   ├── ident-func.png
    │   │   │   ├── ipcg-func.png
    │   │   │   ├── ipcg-pkg.png
    │   │   │   ├── typeinfo-pkg.png
    │   │   │   └── typeinfo-src.png
    │   │   ├── callgraph.html
    │   │   ├── codewalkdir.html
    │   │   ├── codewalk.html
    │   │   ├── dirlist.html
    │   │   ├── doc.go
    │   │   ├── error.html
    │   │   ├── example.html
    │   │   ├── gen.go
    │   │   ├── gen_test.go
    │   │   ├── godoc.html
    │   │   ├── godocs.js
    │   │   ├── images
    │   │   │   ├── minus.gif
    │   │   │   ├── plus.gif
    │   │   │   ├── treeview-black.gif
    │   │   │   ├── treeview-black-line.gif
    │   │   │   ├── treeview-default.gif
    │   │   │   ├── treeview-default-line.gif
    │   │   │   ├── treeview-gray.gif
    │   │   │   └── treeview-gray-line.gif
    │   │   ├── implements.html
    │   │   ├── jquery.js
    │   │   ├── jquery.treeview.css
    │   │   ├── jquery.treeview.edit.js
    │   │   ├── jquery.treeview.js
    │   │   ├── makestatic.go
    │   │   ├── methodset.html
    │   │   ├── opensearch.xml
    │   │   ├── package.html
    │   │   ├── packageroot.html
    │   │   ├── playground.js
    │   │   ├── play.js
    │   │   ├── searchcode.html
    │   │   ├── searchdoc.html
    │   │   ├── search.html
    │   │   ├── searchtxt.html
    │   │   ├── static.go
    │   │   └── style.css
    │   ├── tab.go
    │   ├── template.go
    │   ├── util
    │   │   ├── throttle.go
    │   │   └── util.go
    │   ├── versions.go
    │   ├── versions_test.go
    │   └── vfs
    │       ├── emptyvfs.go
    │       ├── gatefs
    │       │   ├── gatefs.go
    │       │   └── gatefs_test.go
    │       ├── httpfs
    │       │   └── httpfs.go
    │       ├── mapfs
    │       │   ├── mapfs.go
    │       │   └── mapfs_test.go
    │       ├── namespace.go
    │       ├── namespace_test.go
    │       ├── os.go
    │       ├── os_test.go
    │       ├── vfs.go
    │       └── zipfs
    │           ├── zipfs.go
    │           └── zipfs_test.go
    ├── go.mod
    ├── gopls
    │   ├── doc
    │   │   ├── acme.md
    │   │   ├── command-line.md
    │   │   ├── contributing.md
    │   │   ├── design.md
    │   │   ├── emacs.md
    │   │   ├── faq.md
    │   │   ├── implementation.md
    │   │   ├── integrating.md
    │   │   ├── settings.md
    │   │   ├── status.md
    │   │   ├── subl.md
    │   │   ├── troubleshooting.md
    │   │   ├── user.md
    │   │   ├── vim.md
    │   │   └── vscode.md
    │   ├── go.mod
    │   ├── go.sum
    │   ├── internal
    │   │   └── hooks
    │   │       ├── analysis.go
    │   │       ├── diff.go
    │   │       ├── diff_test.go
    │   │       └── hooks.go
    │   ├── main.go
    │   ├── README.md
    │   └── test
    │       └── gopls_test.go
    ├── go.sum
    ├── imports
    │   └── forward.go
    ├── internal
    │   ├── apidiff
    │   │   ├── apidiff.go
    │   │   ├── apidiff_test.go
    │   │   ├── compatibility.go
    │   │   ├── correspondence.go
    │   │   ├── messageset.go
    │   │   ├── README.md
    │   │   ├── report.go
    │   │   └── testdata
    │   │       ├── exported_fields
    │   │       │   └── ef.go
    │   │       └── tests.go
    │   ├── fastwalk
    │   │   ├── fastwalk_dirent_fileno.go
    │   │   ├── fastwalk_dirent_ino.go
    │   │   ├── fastwalk_dirent_namlen_bsd.go
    │   │   ├── fastwalk_dirent_namlen_linux.go
    │   │   ├── fastwalk.go
    │   │   ├── fastwalk_portable.go
    │   │   ├── fastwalk_test.go
    │   │   └── fastwalk_unix.go
    │   ├── gopathwalk
    │   │   ├── walk.go
    │   │   └── walk_test.go
    │   ├── imports
    │   │   ├── fix.go
    │   │   ├── fix_test.go
    │   │   ├── imports.go
    │   │   ├── imports_test.go
    │   │   ├── mkindex.go
    │   │   ├── mkstdlib.go
    │   │   ├── mod_112_test.go
    │   │   ├── mod_114_test.go
    │   │   ├── mod_cache.go
    │   │   ├── mod_cache_test.go
    │   │   ├── mod.go
    │   │   ├── mod_pre114_test.go
    │   │   ├── mod_test.go
    │   │   ├── proxy_112_test.go
    │   │   ├── proxy_113_test.go
    │   │   ├── sortimports.go
    │   │   ├── testdata
    │   │   │   └── mod
    │   │   │       ├── example.com_v1.0.0.txt
    │   │   │       ├── golang.org_x_text_v0.0.0-20170915032832-14c0d48ead0c.txt
    │   │   │       ├── rsc.io_quote_v1.5.1.txt
    │   │   │       ├── rsc.io_!q!u!o!t!e_v1.5.2.txt
    │   │   │       ├── rsc.io_quote_v1.5.2.txt
    │   │   │       ├── rsc.io_!q!u!o!t!e_v1.5.3-!p!r!e.txt
    │   │   │       ├── rsc.io_quote_v2_v2.0.1.txt
    │   │   │       ├── rsc.io_quote_v3_v3.0.0.txt
    │   │   │       ├── rsc.io_sampler_v1.3.0.txt
    │   │   │       └── rsc.io_sampler_v1.3.1.txt
    │   │   └── zstdlib.go
    │   ├── jsonrpc2
    │   │   ├── handler.go
    │   │   ├── jsonrpc2.go
    │   │   ├── jsonrpc2_test.go
    │   │   ├── stream.go
    │   │   └── wire.go
    │   ├── lsp
    │   │   ├── browser
    │   │   │   ├── browser.go
    │   │   │   └── README.md
    │   │   ├── cache
    │   │   │   ├── analysis.go
    │   │   │   ├── builtin.go
    │   │   │   ├── cache.go
    │   │   │   ├── check.go
    │   │   │   ├── errors.go
    │   │   │   ├── error_test.go
    │   │   │   ├── external.go
    │   │   │   ├── file.go
    │   │   │   ├── gofile.go
    │   │   │   ├── load.go
    │   │   │   ├── parse.go
    │   │   │   ├── pkg.go
    │   │   │   ├── session.go
    │   │   │   ├── snapshot.go
    │   │   │   ├── view.go
    │   │   │   └── watcher.go
    │   │   ├── cmd
    │   │   │   ├── check.go
    │   │   │   ├── cmd.go
    │   │   │   ├── cmd_test.go
    │   │   │   ├── definition.go
    │   │   │   ├── export_test.go
    │   │   │   ├── folding_range.go
    │   │   │   ├── format.go
    │   │   │   ├── imports.go
    │   │   │   ├── info.go
    │   │   │   ├── links.go
    │   │   │   ├── query.go
    │   │   │   ├── references.go
    │   │   │   ├── rename.go
    │   │   │   ├── serve.go
    │   │   │   ├── signature.go
    │   │   │   ├── suggested_fix.go
    │   │   │   ├── symbols.go
    │   │   │   └── test
    │   │   │       ├── check.go
    │   │   │       ├── cmdtest.go
    │   │   │       ├── definition.go
    │   │   │       ├── folding_range.go
    │   │   │       ├── format.go
    │   │   │       ├── imports.go
    │   │   │       ├── links.go
    │   │   │       ├── references.go
    │   │   │       ├── rename.go
    │   │   │       ├── signature.go
    │   │   │       ├── suggested_fix.go
    │   │   │       └── symbols.go
    │   │   ├── code_action.go
    │   │   ├── command.go
    │   │   ├── completion.go
    │   │   ├── completion_test.go
    │   │   ├── debug
    │   │   │   ├── info.1.11.go
    │   │   │   ├── info.1.12.go
    │   │   │   ├── info.go
    │   │   │   ├── metrics.go
    │   │   │   ├── rpc.go
    │   │   │   ├── serve.go
    │   │   │   └── trace.go
    │   │   ├── definition.go
    │   │   ├── diagnostics.go
    │   │   ├── diff
    │   │   │   ├── diff.go
    │   │   │   ├── difftest
    │   │   │   │   ├── difftest.go
    │   │   │   │   └── difftest_test.go
    │   │   │   ├── diff_test.go
    │   │   │   ├── myers
    │   │   │   │   ├── diff.go
    │   │   │   │   └── diff_test.go
    │   │   │   └── unified.go
    │   │   ├── folding_range.go
    │   │   ├── format.go
    │   │   ├── fuzzy
    │   │   │   ├── input.go
    │   │   │   ├── input_test.go
    │   │   │   ├── matcher.go
    │   │   │   └── matcher_test.go
    │   │   ├── general.go
    │   │   ├── highlight.go
    │   │   ├── hover.go
    │   │   ├── implementation.go
    │   │   ├── link.go
    │   │   ├── lsp_test.go
    │   │   ├── protocol
    │   │   │   ├── context.go
    │   │   │   ├── doc.go
    │   │   │   ├── enums.go
    │   │   │   ├── log.go
    │   │   │   ├── protocol.go
    │   │   │   ├── span.go
    │   │   │   ├── tsclient.go
    │   │   │   ├── tsprotocol.go
    │   │   │   ├── tsserver.go
    │   │   │   └── typescript
    │   │   │       ├── go.ts
    │   │   │       ├── README.md
    │   │   │       └── requests.ts
    │   │   ├── references.go
    │   │   ├── rename.go
    │   │   ├── reset_golden.sh
    │   │   ├── server.go
    │   │   ├── signature_help.go
    │   │   ├── snippet
    │   │   │   ├── snippet_builder.go
    │   │   │   └── snippet_builder_test.go
    │   │   ├── source
    │   │   │   ├── comment.go
    │   │   │   ├── comment_test.go
    │   │   │   ├── completion_format.go
    │   │   │   ├── completion.go
    │   │   │   ├── completion_keywords.go
    │   │   │   ├── completion_labels.go
    │   │   │   ├── completion_literal.go
    │   │   │   ├── completion_snippet.go
    │   │   │   ├── deep_completion.go
    │   │   │   ├── diagnostics.go
    │   │   │   ├── errors.go
    │   │   │   ├── folding_range.go
    │   │   │   ├── format.go
    │   │   │   ├── highlight.go
    │   │   │   ├── hover.go
    │   │   │   ├── identifier.go
    │   │   │   ├── implementation.go
    │   │   │   ├── options.go
    │   │   │   ├── references.go
    │   │   │   ├── rename_check.go
    │   │   │   ├── rename.go
    │   │   │   ├── signature_help.go
    │   │   │   ├── source_test.go
    │   │   │   ├── suggested_fix.go
    │   │   │   ├── symbols.go
    │   │   │   ├── tidy.go
    │   │   │   ├── util.go
    │   │   │   └── view.go
    │   │   ├── symbols.go
    │   │   ├── telemetry
    │   │   │   └── telemetry.go
    │   │   ├── testdata
    │   │   │   ├── analyzer
    │   │   │   │   └── bad_test.go
    │   │   │   ├── anon
    │   │   │   │   └── anon.go.in
    │   │   │   ├── append
    │   │   │   │   └── append.go
    │   │   │   ├── arraytype
    │   │   │   │   └── array_type.go.in
    │   │   │   ├── bad
    │   │   │   │   ├── bad0.go
    │   │   │   │   ├── bad1.go
    │   │   │   │   └── badimport.go
    │   │   │   ├── badstmt
    │   │   │   │   ├── badstmt_2.go.in
    │   │   │   │   ├── badstmt_3.go.in
    │   │   │   │   ├── badstmt_4.go.in
    │   │   │   │   └── badstmt.go.in
    │   │   │   ├── bar
    │   │   │   │   └── bar.go.in
    │   │   │   ├── basiclit
    │   │   │   │   └── basiclit.go
    │   │   │   ├── baz
    │   │   │   │   └── baz.go.in
    │   │   │   ├── builtins
    │   │   │   │   ├── builtins.go
    │   │   │   │   └── iota.go
    │   │   │   ├── casesensitive
    │   │   │   │   └── casesensitive.go
    │   │   │   ├── cast
    │   │   │   │   └── cast.go.in
    │   │   │   ├── channel
    │   │   │   │   └── channel.go
    │   │   │   ├── comments
    │   │   │   │   └── comments.go
    │   │   │   ├── complit
    │   │   │   │   └── complit.go.in
    │   │   │   ├── constant
    │   │   │   │   └── constant.go
    │   │   │   ├── deep
    │   │   │   │   └── deep.go
    │   │   │   ├── errors
    │   │   │   │   └── errors.go
    │   │   │   ├── fieldlist
    │   │   │   │   └── field_list.go
    │   │   │   ├── folding
    │   │   │   │   ├── a.go
    │   │   │   │   ├── a.go.golden
    │   │   │   │   ├── bad.go.golden
    │   │   │   │   └── bad.go.in
    │   │   │   ├── foo
    │   │   │   │   └── foo.go
    │   │   │   ├── format
    │   │   │   │   ├── bad_format.go.golden
    │   │   │   │   ├── bad_format.go.in
    │   │   │   │   ├── good_format.go
    │   │   │   │   ├── good_format.go.golden
    │   │   │   │   ├── newline_format.go.golden
    │   │   │   │   ├── newline_format.go.in
    │   │   │   │   ├── one_line.go.golden
    │   │   │   │   └── one_line.go.in
    │   │   │   ├── func_rank
    │   │   │   │   └── func_rank.go.in
    │   │   │   ├── funcsig
    │   │   │   │   └── func_sig.go
    │   │   │   ├── funcvalue
    │   │   │   │   └── func_value.go
    │   │   │   ├── fuzzy
    │   │   │   │   └── fuzzy.go
    │   │   │   ├── generated
    │   │   │   │   ├── generated.go
    │   │   │   │   └── generator.go
    │   │   │   ├── godef
    │   │   │   │   ├── a
    │   │   │   │   │   ├── a.go
    │   │   │   │   │   ├── a.go.golden
    │   │   │   │   │   ├── d.go
    │   │   │   │   │   ├── d.go.golden
    │   │   │   │   │   ├── f.go
    │   │   │   │   │   ├── f.go.golden
    │   │   │   │   │   ├── random.go
    │   │   │   │   │   └── random.go.golden
    │   │   │   │   ├── b
    │   │   │   │   │   ├── b.go
    │   │   │   │   │   ├── b.go.golden
    │   │   │   │   │   ├── c.go
    │   │   │   │   │   ├── c.go.golden
    │   │   │   │   │   ├── c.go.saved
    │   │   │   │   │   ├── e.go
    │   │   │   │   │   └── e.go.golden
    │   │   │   │   └── broken
    │   │   │   │       ├── unclosedIf.go.golden
    │   │   │   │       └── unclosedIf.go.in
    │   │   │   ├── good
    │   │   │   │   ├── good0.go
    │   │   │   │   └── good1.go
    │   │   │   ├── highlights
    │   │   │   │   └── highlights.go
    │   │   │   ├── implementation
    │   │   │   │   ├── implementation.go
    │   │   │   │   └── other
    │   │   │   │       └── other.go
    │   │   │   ├── importedcomplit
    │   │   │   │   └── imported_complit.go
    │   │   │   ├── imports
    │   │   │   │   ├── add_import.go.golden
    │   │   │   │   ├── add_import.go.in
    │   │   │   │   ├── good_imports.go.golden
    │   │   │   │   ├── good_imports.go.in
    │   │   │   │   ├── issue35458.go.golden
    │   │   │   │   ├── issue35458.go.in
    │   │   │   │   ├── multiple_blocks.go.golden
    │   │   │   │   ├── multiple_blocks.go.in
    │   │   │   │   ├── needs_imports.go.golden
    │   │   │   │   ├── needs_imports.go.in
    │   │   │   │   ├── remove_import.go.golden
    │   │   │   │   ├── remove_import.go.in
    │   │   │   │   ├── remove_imports.go.golden
    │   │   │   │   └── remove_imports.go.in
    │   │   │   ├── index
    │   │   │   │   └── index.go
    │   │   │   ├── interfacerank
    │   │   │   │   └── interface_rank.go
    │   │   │   ├── keywords
    │   │   │   │   └── keywords.go
    │   │   │   ├── labels
    │   │   │   │   └── labels.go
    │   │   │   ├── links
    │   │   │   │   └── links.go
    │   │   │   ├── maps
    │   │   │   │   └── maps.go.in
    │   │   │   ├── nested_complit
    │   │   │   │   └── nested_complit.go.in
    │   │   │   ├── nodisk
    │   │   │   │   ├── empty
    │   │   │   │   └── nodisk.overlay.go
    │   │   │   ├── noparse
    │   │   │   │   └── noparse.go.in
    │   │   │   ├── noparse_format
    │   │   │   │   ├── noparse_format.go.golden
    │   │   │   │   ├── noparse_format.go.in
    │   │   │   │   ├── parse_format.go.golden
    │   │   │   │   └── parse_format.go.in
    │   │   │   ├── rank
    │   │   │   │   ├── assign_rank.go.in
    │   │   │   │   ├── binexpr_rank.go.in
    │   │   │   │   ├── convert_rank.go.in
    │   │   │   │   ├── switch_rank.go.in
    │   │   │   │   ├── type_assert_rank.go.in
    │   │   │   │   └── type_switch_rank.go.in
    │   │   │   ├── references
    │   │   │   │   └── refs.go
    │   │   │   ├── rename
    │   │   │   │   ├── a
    │   │   │   │   │   ├── random.go.golden
    │   │   │   │   │   └── random.go.in
    │   │   │   │   ├── b
    │   │   │   │   │   ├── b.go
    │   │   │   │   │   └── b.go.golden
    │   │   │   │   ├── bad
    │   │   │   │   │   ├── bad.go.golden
    │   │   │   │   │   ├── bad.go.in
    │   │   │   │   │   └── bad_test.go.in
    │   │   │   │   └── testy
    │   │   │   │       ├── testy.go
    │   │   │   │       ├── testy.go.golden
    │   │   │   │       ├── testy_test.go
    │   │   │   │       └── testy_test.go.golden
    │   │   │   ├── selector
    │   │   │   │   └── selector.go.in
    │   │   │   ├── signature
    │   │   │   │   ├── signature.go
    │   │   │   │   └── signature.go.golden
    │   │   │   ├── snippets
    │   │   │   │   ├── literal_snippets.go.in
    │   │   │   │   └── snippets.go.in
    │   │   │   ├── suggestedfix
    │   │   │   │   ├── has_suggested_fix.go
    │   │   │   │   └── has_suggested_fix.go.golden
    │   │   │   ├── summary.txt.golden
    │   │   │   ├── symbols
    │   │   │   │   ├── main.go
    │   │   │   │   └── main.go.golden
    │   │   │   ├── testy
    │   │   │   │   ├── testy.go
    │   │   │   │   └── testy_test.go
    │   │   │   ├── typeassert
    │   │   │   │   └── type_assert.go
    │   │   │   ├── types
    │   │   │   │   └── types.go
    │   │   │   ├── unimported
    │   │   │   │   ├── unimported_cand_type.go
    │   │   │   │   └── unimported.go.in
    │   │   │   ├── unresolved
    │   │   │   │   └── unresolved.go.in
    │   │   │   ├── unsafe
    │   │   │   │   └── unsafe.go
    │   │   │   └── variadic
    │   │   │       └── variadic.go.in
    │   │   ├── tests
    │   │   │   ├── completion.go
    │   │   │   ├── diagnostics.go
    │   │   │   ├── links.go
    │   │   │   └── tests.go
    │   │   ├── text_synchronization.go
    │   │   ├── watched_files.go
    │   │   └── workspace.go
    │   ├── memoize
    │   │   ├── memoize.go
    │   │   ├── memoize_test.go
    │   │   └── nocopy.go
    │   ├── module
    │   │   ├── module.go
    │   │   └── module_test.go
    │   ├── semver
    │   │   ├── semver.go
    │   │   └── semver_test.go
    │   ├── span
    │   │   ├── parse.go
    │   │   ├── span.go
    │   │   ├── span_test.go
    │   │   ├── token111.go
    │   │   ├── token112.go
    │   │   ├── token.go
    │   │   ├── token_test.go
    │   │   ├── uri.go
    │   │   ├── uri_test.go
    │   │   ├── utf16.go
    │   │   └── utf16_test.go
    │   ├── telemetry
    │   │   ├── context.go
    │   │   ├── doc.go
    │   │   ├── event.go
    │   │   ├── export
    │   │   │   ├── export.go
    │   │   │   ├── log.go
    │   │   │   ├── multi.go
    │   │   │   ├── null.go
    │   │   │   ├── ocagent
    │   │   │   │   ├── metrics.go
    │   │   │   │   ├── metrics_test.go
    │   │   │   │   ├── ocagent.go
    │   │   │   │   ├── ocagent_test.go
    │   │   │   │   └── wire
    │   │   │   │       ├── common.go
    │   │   │   │       ├── core.go
    │   │   │   │       ├── metrics.go
    │   │   │   │       └── trace.go
    │   │   │   └── prometheus
    │   │   │       └── prometheus.go
    │   │   ├── id.go
    │   │   ├── log
    │   │   │   └── log.go
    │   │   ├── metric
    │   │   │   └── metric.go
    │   │   ├── metric.go
    │   │   ├── stats
    │   │   │   ├── stats.go
    │   │   │   └── worker.go
    │   │   ├── tag
    │   │   │   ├── key.go
    │   │   │   └── tag.go
    │   │   ├── tag.go
    │   │   ├── trace
    │   │   │   └── trace.go
    │   │   ├── trace.go
    │   │   └── unit
    │   │       └── unit.go
    │   ├── testenv
    │   │   ├── testenv_112.go
    │   │   └── testenv.go
    │   ├── tool
    │   │   └── tool.go
    │   ├── txtar
    │   │   ├── archive.go
    │   │   └── archive_test.go
    │   └── xcontext
    │       └── xcontext.go
    ├── LICENSE
    ├── PATENTS
    ├── playground
    │   ├── playground.go
    │   └── socket
    │       ├── socket.go
    │       └── socket_test.go
    ├── present
    │   ├── args.go
    │   ├── caption.go
    │   ├── code.go
    │   ├── code_test.go
    │   ├── doc.go
    │   ├── html.go
    │   ├── iframe.go
    │   ├── image.go
    │   ├── link.go
    │   ├── link_test.go
    │   ├── parse.go
    │   ├── style.go
    │   ├── style_test.go
    │   └── video.go
    ├── README.md
    └── refactor
        ├── eg
        │   ├── eg.go
        │   ├── eg_test.go
        │   ├── match.go
        │   ├── rewrite.go
        │   └── testdata
        │       ├── A1.go
        │       ├── A1.golden
        │       ├── A2.go
        │       ├── A2.golden
        │       ├── A.template
        │       ├── B1.go
        │       ├── B1.golden
        │       ├── bad_type.template
        │       ├── B.template
        │       ├── C1.go
        │       ├── C1.golden
        │       ├── C.template
        │       ├── D1.go
        │       ├── D1.golden
        │       ├── D.template
        │       ├── E1.go
        │       ├── E1.golden
        │       ├── E.template
        │       ├── expr_type_mismatch.template
        │       ├── F1.go
        │       ├── F1.golden
        │       ├── F.template
        │       ├── G1.go
        │       ├── G1.golden
        │       ├── G.template
        │       ├── H1.go
        │       ├── H1.golden
        │       ├── H.template
        │       ├── I1.go
        │       ├── I1.golden
        │       ├── I.template
        │       ├── J1.go
        │       ├── J1.golden
        │       ├── J.template
        │       ├── no_after_return.template
        │       ├── no_before.template
        │       └── type_mismatch.template
        ├── importgraph
        │   ├── graph.go
        │   └── graph_test.go
        ├── README
        ├── rename
        │   ├── check.go
        │   ├── mvpkg.go
        │   ├── mvpkg_test.go
        │   ├── rename.go
        │   ├── rename_test.go
        │   ├── spec.go
        │   └── util.go
        └── satisfy
            └── find.go

1160 directories, 5988 files

```