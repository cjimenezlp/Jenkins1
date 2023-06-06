pipeline
{
    agent any
    stages
    {
        
		stage("inter")
        {
            
            steps
            {
                
                script
                {
					cadena = "MI artista favotito es Fito Paez, lo esccuho de sde que era joven,+ "\n"+ canciones como Giros, Mariposa Technicolor, Brillante sobre el MIC + "\n"+ son unas de mis canciones preferidas"
					writeFile(file: "salida.txt", text: cadena)
                }
            }
            
        }
        
    }
}
