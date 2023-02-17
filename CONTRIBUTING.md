npm install react-native-svg

# Import"chatbot"from

# chatterbot package

from chatterbot import ChatBot

# Inorder to train our bot, we have

# to import a trainer package

# "ChatterBotCorpusTrainer"

from chatterbot.trainers import ChatterBotCorpusTrainer

# Give a name to the chatbot “It”

# and assign a trainer component

chatbot=ChatBot(It bot')
 [#15](https://github.com/arabnewscms/it/issues/15)

# Create a new trainer for the chatbot

trainer =
ChatterBotCorpusTrainer(chatbot)

#   [import { makeStyles, Box, Grid } from "@material-ui/core";
import React, { useState } from "react";
import Header from "./header";
import contractPdf from "../../sample.pdf";
import { Document, Page } from "react-pdf";

const useStyles = makeStyles((theme) => ({
  root: {
    padding: "32px 24px 14px 24px",
  },
  pdfArea: {
    borderRight: "1px solid #DDDDDD",
    height: "calc(100vh - 195px)",
  },
}));


const BasicComponent = (props) => {
  const classes = useStyles();
  const [numPages, setNumPages] = useState(null);
  const [pageNumber, setPageNumber] = useState(1);


# Now let us train our bot with multiple corpus

trainer.train("chatterbot.corpus.english.greetings",
 "chatterbot.corpus.english.conversations")
  
response = chatbot.get_response('What is your Number')
print(response)

response = chatbot.get_response('Who are you?')
print(response){}
