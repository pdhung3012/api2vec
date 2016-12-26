# Api2vecJava

1. Get vector representation for each API in a trained model:
		Run the class com.medallia.word2vec.Word2VecExamples.java with the VM arguments: 
		inputModel "models\java-14000-projects.mod" outputPath "models\vectorRepresentation.txt"
		
		Each line in the vectorRepresentation,txt is in the form of: [API name]\t[dimension of vector]\t[vector]  