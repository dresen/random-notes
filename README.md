# random-notes
notes for papers and other random stuff

Install Atom, add my emacs init.el, texstudio and aegisub
Also anaconda, tensorflow, dynet, kaldi+irstlm, dropbox, skype, spotify,
telegram, terminator, hamachi+haguichi, git, sox

get my repos from github

Install PCSX and change that little ting-a-magick from 0 to 1 so it works



CSL paper outline:

Structure

Intro

  Improving ASR for a specific language
  Challenges: variability, accent, access to data

  Improving models:	GMM -> subspace GMM -> DNN -> RNN/CNN etc
			Linguistic information: phonetics/acoustics

  This article is about Danish stød, ASR, creating an open source setup for research
  What is stød?
  The three questions we need to answer

  Article outline

Review of Danish stød and Danish ASR
  State of Danish ASR
  How can stød be used to improve Danish ASR?
  How is it described by N Grønnum and GF Hansen?
  What is probelmatic about the description
  The Kaldi sprakbanken setup
  Why use Kaldi

Reliability and predictive features
  Can we trust annotation?
  Can we use annotation to rank acoustic features and do feature selection?
  Binary prediction of stød
  Multiclass prediction of stød

Adding stød to Kaldi-based ASR
  Simple extension of the phone set
  Adding pitch
  
