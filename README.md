# MusicPlaylistApp
First page

 Column(){

                    Text("Hello, Welcome to Music Manager App ")

                    Button(onClick = {
                    val intent = Intent(this@MainActivity,AddtoPlaylist::class.java)
                        startActivity(intent)
                    }
                    ) {
                        Text("Add to Playlist")
                    }
                    Button(onClick = {
                        val intent = Intent(this@MainActivity, DetailedView::class.java)
                        startActivity(intent)

                    }
                    ) {
                        Text("Detailed view")
                    }
                    Button(onClick = {finishAffinity()

                    }
                    ) {
                        Text("Exit")
                    }
                }
            }
        }
    }


    2nd Page

    

                Column(){
                    Button(onClick = {

                    }
                    ) {
                        Text("Song Title")
                    }
                    Button(onClick = {

                    }
                    ) {
                        Text("Artist Name")
                    }
                    Button(onClick = {

                    }
                    ) {
                        Text("Rating (1-5)")
                    }
                    Button(onClick = {

                    }
                    ) {
                        Text("Comments")
                    }

                    Row(){
                        Button(onClick = {

                        }
                        ) {
                            Text("Save")
                        }
                        Button(onClick = {
                            val intent = Intent(this@AddtoPlaylist,MainActivity::class.java)
                            startActivity(intent)

                        }
                        ) {
                            Text("Home")
                        }
                    }

                }

            }
        }
    }
}

3rd page



                Column(){

                    Button(onClick = {

                    }) {
                    Text("Display List")

                    }
                    Button(onClick = {

                    }) {
                        Text("Average Rating")

                    }
                    Button(onClick = {
                        val intent = Intent(this@DetailedView, MainActivity::class.java)
                        startActivity(intent)

                    }) {
                        Text("Home")

                    }

                }

            }
        }
    }
}

}

