# ASL-Finger-Spelling

In this project, I compare the accuracy on ASL Fingerspelling translator using supervised             
machine learning.The final system is able to classify 24 different symbols with reasonable             
accuracy.
So in order to recognize the various finger spelled letters we tried various algorithms and later               
compared the accuracybythesealgorithmsnamelyCNN,SVMandANN.AccuracyforSVMwas            
way better when compared to SVM and CNN. The accuracy for CNN was nearly 88% when compared to SVM which was with accuracy of    
about 100%.

INTRODUCTION 
 
American Sign Language (ASL) is one of the main forms of communication among the deaf    
communities. This motivatesustodevelopatranslatorthatcanrecognizehandsymbolsandgive          
us the corresponding meaning as output. A subset of ASL is the American Manual Alphabet        
referred to as fingerspelling - which is used to spell out the 26 different letters of the English     
language using unique hand gestures.. Of these symbols, 24 are static hand postures - the             
exceptions being ’j’ and ’z’. In order to avoid excessive complexity, this project will restrict     
itself to the reduced 24-letter alphabet excluding ’j’ and ’z’.  
 
 
 
 
Fig.1, ASL fingerspelling Symbols 
 
 
In terms of the bigger picture, hand gesture recognition technology can be applied to other          
problems as well, such as interfacing with computers or machinesthroughgestures.Interpreting       
hand movements could also become a way of logging and analyzing human behavior​[3]. On the        
particular problem of fingerspelling interpretation, there has been work done in the recent past.  
For instance, describes a method of fingerspelling translation using a gabor filters. This is the          
case of a feature-based method of translation. Other approaches are known to employ methods         
based on deep learning with convolutional neural networks (CNNs), where feature extraction is      
unnecessary since CNNs are end-to-end solutions. Recently thesedeeplearningapproachestake          
up a dominant position in sign language detection and other computer vision classification             
problems. The approach taken here represents an attempt to create an effective feature-based         
detector and validate its effectivenessontechniquelikeSVMorNaiveBayesascomparedtothe              
deep learning methods. Furthermore, the goal of this project is the comparison between these      
algorithms . 
 
 
