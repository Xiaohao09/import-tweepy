# import-tweepy
consumer_key = "CHICutBOjAjAF8BRGQ0upG7ei"
consumer_secret = "jpqDwiMivYkvilkL4XeMGOJRnQLL64Yn5hHj1cRafwKe6ibRiQ"
access_token = "1103302895590666242-jy2Pp135efB4jk11yZ8BDD800DnWLQ"
access_token_secret = "JKoYHFrhSkLaFI5Lu0WAKQvIinbBZrRSdpQVYTEveYCLw"
# Creating the authentication object
auth = tweepy.OAuthHandler(consumer_key, consumer_secret)
# Setting your access token and secret
auth.set_access_token(access_token, access_token_secret)
# Creating the API object while passing in auth information
api = tweepy.API(auth)
