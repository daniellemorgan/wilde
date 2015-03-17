#Danielle's...Progress Report

#Danielle's Abstract
##March 2, 2015

Where's Wildo?
While Victorian illustration is appreciated for its aesthetic, I want to focus on the emergence of interplay between texts and illustrations in this period, which often unveiled second and sometimes alternate narratives. Aubrey Beardsley's illustrations for Oscar Wilde's _Salome_ not only decoratively enhanced the text but also foregrounded an erotic reading of the play. Scholars also speculate that caricatures of Wilde appear in four instances within Beardsley's illustrations: in the frontispiece, The Face in the Moon, The Eyes of Herod, and The Platonic Lament. Beardsley, Max Beerbohm, and many others also illustrated and published caricatures of Wilde throughout the period. After using Python to create Wilde's eigenface, I will use openCV to run his face against a series of illustrated caricatures in order to determine if facial recognition software can detect faces in illustrations. If this is method proves to be successful it will solidify the argument that Beardsley's illustrations do, in fact, contain caricatures of Wilde. Conversely, this method could be used to spur research opportunities. A specific eigenface could be run against a larger database of illustrations in order to see possible instances of caricature that may not be immediately obvious to the human eye. This method could also uncover possible relationships between illustrators, authors, and other public figures. Using Python and OpenCV, I will help solidify the assumption that Beardsley caricatures Wilde in _Salome_ and hopefully this method provokes research opportunities concerning relationships between other illustrators and authors in the Victorian era.
I know that I will only be able to run Wilde's eigenface against a few images because it takes quite a bit of time to run the software. If I had more time I would love to run it against a huge database of Victorian illustrations and see if it comes up with anything unexpected. 

I am currently having difficulty downloading OpenCV to my computer because I have Yosemite downloaded. Once I figure that out I should be able to continue using Terrence Eden's eigenface creation and run Wilde against his caricatures. 

If I were to write an essay about my findings I could submit it to the Victorian Literature and Culture Journal. 

#Danielle's Annotated Bibliography
##February 14, 2015

Au, Carmen, Jean-Sebastien Legare, and Reehan Shaikh. "Face Recognition: Robustness of the 'Eigenface' Approach" Quebec: McGill University School of Computer Science and Center for Intelligent Machines. Print. 
-outlines possible "flaws" or differences in images that could affect facial detection including brightness, patial occlusion, facial tilting, and image noise. 
-tests varying brightness, noise, and occlusion levels to gauge at what point the algorithm will fail
Though this article refers to real-life situations, this article provides helpful information that I can apply to my selection of photographs for Wilde's eigenface (for example, gathering many different facial postures and images with varying exposure and noise levels).

Bradski, Gary, and Adrian Kaehler. _Learning OpenCV._ California: O'Reilly Media, 2008. Print. 
-instructions on intalling, using, and applying OpenCV 
-provides sample code
-overview of algorithms for eigenface technique 
This book provides a basic introduction to using OpenCV. I will use it to set up the program and learn to use it before trying to use Eden's code. 

Eden, Terrence. "Which Painting Do You Look Like? Comparing Faces Using Python and OpenCV" _Terrence Eden's Blog_ shkspr.mobi, 14 Jun. 2014. Web. 14 Jun. 2015.
-quick overview of coding and building eigenfaces
-provides code that Eden used to run faces against paintings in the Tate Museum
I can use Eden's code in order to create Wilde's eigenface. It is also helpful to know that this software is able to pick out faces in artwork.

Gilbert, Elliot L. "Tumult of Images: Wilde, Beardsley, and _Salome._" _Victorian Studies_ 26.2 (1983): 133-59. Web. 14 Feb 2015. 
-outlines relationship between Beardsley and Wilde
-engages arguments over whether Beardsley's caricatures are criticisms of Wilde's "feminine nature" or a praise of the autobiographical/caricature elements of the play.
May help to outline motivations behind the caricatures in the play and the many possible reasons for Beardsley's inclusion of Wilde's face in the illustrations. 

Goldman, Jonathan. _Modernism is the Literature of Celebrity._ Texas: University of Texas Press, 2011. Print. 
-explores the effect caricatures had on Wilde and his work
-reveals use of caricature and stereotype in Wilde's written works (specifically _Dorian Gray_)
This book helps situate my research of visual caricature into a wider context of textual caricature and Wilde's role in the creation of his own persona/celebrity. 

Holland, Vyvyan. _Oscar Wilde: a pictorial biography._ London: Thames and Hudson, 1960. Print. 
-photographs of Wilde's face (various angles and expressions)
-popular caricatures of Wilde 
-textual and pictorial timeline 
This book provides a linear collection of photographs of Wilde, which I can use to create an eigenface and run it against the illustrated caricatures. It also provides context for famous caricatures.

Lynch, Bohun. _A History of Caricature._ Boston: Little, Brown, and Company, 1927. Web. 14 Feb. 2015. 
-provides survey of famous caricaturists
-focuses on the insurgence of caricature in eighteenth century England
-examples of the type of exaggeration present in caricature (focus on very specific aspects of the face and body)
This book will help me gain insight into the reasons for Victorian obsession with caricature and will help me pinpoint the specific exaggerations typically applied to caricatures of Wilde. 

Navarre, Joan. "Paul Verlaine and A Platonic Lament: Beardsley's Portrayal of a Parallel Love story in Wilde's Salome." _English Literature in Transition, 1880-1920._ 51.2 (2008):152-63. Web. 14 Feb. 2015. 
-asserts that Wilde is not caricatured in malice but rather, because his illustrations allude to a relationship between Verlaine and Rimbaud, Beardsley uses caricature to applaud the spirit of Wilde's play. 
provides an alternate argument for the motivations behind Beardsley's caricatures. I want to gather as many interpretations surrounding these caricatures as possible. 

OpenCV Dev Team. "Face Recognition with OpenCv" _OpenCV._ docs.opencv.org, 21 Apr. 2014. Web. 14 Feb. 2015. 
-Step-by-step instruction on using OpenCV and creating eigenfaces
-provides source code (in attached src) for eigenface creation 
-instructions for cropping/scaling photograph
These instructions pinpoint important lines within the code and expand on the creation of an eigenface. This will provide a better understanding of Eden's code as I use it to create Wilde's eigenface.

Skelly, Julia. _The Uses of Excess in Visual and Material Culture, 1600-2010._ Surrey: Ashgate Publishing Limited, 2014. Print.
-focus on Wilde's mouth and teeth in caricatures
-talks about exaggeration of the shape of Wilde's "Pear-shaped head" (Skelly 142).
-references to lesser-known caricatures (_A Voluptuary_)
Skelly's book will provide insight into troubles I might run into because of purposeful exaggerations and deformities present in caricatures.  

Wilde, Oscar. _Salome._ London: J. Lane, 1912. Web. 1 Feb. 2015. 
I will be using Oscar Wilde's _Salome_ and Aubrey Beardsley's illustrations as my main primary source. 

#Danielle's Revised Thought Piece
##February 1, 2015

The relationship between Oscar Wilde and Aubrey Beardsley recieves a lot of attention as does the interplay between Wilde's _Salome_ and Beardsley's illustrations of it. Scholars speculate that there are four separate caricatures of Wilde incorporated into Beardsley's illustrations. Beardsley also made a few other caricatures of Wilde. It was not, however, exactly novel to create ironic or satirical caricatures of Wilde; these exaggerated images permeated newspapers throughout the Victorian era. I want to solidify assertions that Beardsley's illustrations are caricatures of Wilde and uncover other possible caricatures that may not be entirely obvious to us at first glance. 

I will use OpenCV and Terrence Eden's code in order to create Wilde's eigenface. I will then run this against possible caricatures of Wilde in order to determine if I can match photographs to illustrations. If successful, I can apply my findings to help prove not only that Beardsley made these caricatures of Wilde but, as Susan Owens specualtes in "Aubrey Beardsley, Salome and Satire," that Beardsley used one single photograph as inspiration for his drawings. Hopefully, this use of facial detection software leads to the solidification of current arguments over Wilde caricatures and to further research into possible visual references made throughout Victorian illustration history. This could be an invaluable tool for discovering previously unconnected links between illustrators, authors, and public figures. It would also be a useful research resource if you could search a repository of illustrations for representations/caricatures of a specific person. 

I will be using Beardsley's illustrations for Salome and his extraneous caricatures of Wilde. I will also use some caricatures created by Max Beerbohm. 

Bibliography: 

Kooistra, Lorraine Janzen. _The Artist as Critic: bitextuality in fin-de-siecle illustrated books_ Aldershot: Scolar Press, 1995. Print. 

Owens, Susan. "Aubrey Beardsley, Salome and Satire" London: University College London, 2002. Web. 1 Feb. 2015. 

Wilde, Oscar. _Salome_ London: J. Lane, 1912. Web. 1 Feb. 2015. 

#Danielle's Thought Piece

##January 27, 2015

Scholars debate whether Oscar Wilde's fairy tales should remain in the category of children's literature. With a focus on "The Nightingale and the Rose," I want to suggest that, if understood ironically, Wilde's tales are not anti-moral but rather criticize the pervasiveness of a didactic moral voice in children's literature in the Victorian era. Children, however, lack the ability to recognize irony. Through interplay between text and illustration in P.Craig Russell's version of Wilde's tale, he reveals and reifies this irony.

How does illustration work to not only reiterate texts but work to reify readers and even create alternate visual narratives? Also, what is revealed from readers' illustrated perspective?

Digital archives allow access to various illustrated versions of Wilde's fairy tales, which gives me a linear narrative of how illustrators have visually interpreted Wilde's tales since publication. By using differing forms of illustration, I want to deform (through addition of illustration) Wilde's text in order to explore the ways in which alternate narratives affect the tale. I am able to easily display these illustrations using Scalar. Scalar will also provide a platform on which readers can annotate using images rather than text. I can then contextualize the text within a community of readers/illustrators. I want to show that illustration not only shapes reader perception of a text but that arguments can be made simply through an illustration. 

My argument will be a media-rich narrative using mainly images to show the effect of illustration on Wilde's ironic tale. I chose this type of argument because I want to create visual representations and provide an alternate narrative in order to critique Wilde's tale in a way that could not be achieved through textual representation alone. I also want to use Scalar to create a collaborative, visual conversation that allows me to not only explore how the design of Wilde's book affects meaning but how designing (or illustrating) can actually form a critique of the tale.

Recipe:

-illustrator 

-Scalar 

-Digital PDFs of illustrated Wilde fairy tales

-I was inspired by Ruecker's discussion of the 1518 edition of _Utopia_ and the comment about the woodcuts that frame the book and the subsequent letters that annotated this visual representation. 

Bibliography:

Galey, Alan, and Stan Ruecker. "How a Prototype Argues." _Literary and Linguistic Computing_ 25.4 (2010): 405-424. Web. Jan 26. 2015. 
Kummerling-Meibauer, Bettina. "Metalinguistic Awareness and the Child's Developing Concept of Irony: The Relationship between Pictures and Text in Ironic Picture Books." _The Lion and the Unicorn 23.2 (1999): 157-183. _The John Hopkins University Press._ Web. 26 Jan. 2015. 
Russell, P. Craig. _The Fairy Tales of Oscar Wilde._ New York: Nantier Beall Minoustchine Publishing Inc, 1992. Print.  
Wilde, Oscar. Ed. John Sloan "The Nightingale and the Rose" _The Complete Short Stories_. Oxford: Oxford University Press, 1980. 79-84. Print. 

# After Hermeneutics?
## January 19, 2015 
Galloway's depictions of different mediation are persuasive but I am skeptical of his assertion that one type of mediation can take over another. He suggests, as a mode of mediation, distant reading will dominate deep reading (Hermeneutic) or deep immersion (iridescent reading) because distant reading proves more efficient. What is distant reading doing more efficiently? Mediating? Interpreting? Unveiling the truth? It does not seem that one kind of mediation can dominate another if they perform entirely different tasks: if Hermes questions the truth and Iris admires the truth then the Furies do not look for it. If we are to accept Galloway's claim, instead of interpreting a poem or proposing a problem, we must confront a system, which gives black-boxed mediation and provides information but never immerses or questions. Scholars become curators and arrangers of information, constantly transforming and deforming but never attempting to answer questions. If we forgo hermeneutic and iridescent reading, how can we classify a text as literature? If we do not interpret a text nor appreciate its aesthetic then nothing differentiates T.S. Eliot from a twitter feed. Furthermore, would it matter what kind of media we work with? If we simply scan, make diagrams, and curate information it does not seem to matter if the media we study is watched, read, or listened to. I call this type of scholarship post-media (we are no longer part of the mediation process and the physical media we work with is inconsequential). If we no longer look for hidden truths, we are also in a post-hermeneutical and post-critical state. Although Galloway claims that the middles can dominate each other, I do not think he is lamenting or endorsing the system's take over of hermeneutical and iridescent reading. Rather, he suggests that, like Aphrodite, we are lovers of the middle and within this middle we gain gain something from Hermes, Iris, and the Furies. While the middles may dominate each other, ultimately we dominate the middles.
