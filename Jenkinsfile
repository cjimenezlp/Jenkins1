pipeline
{
    agent any
    stages
    {
        stage("Nombre")
        {
            steps
            {
                script
                {
                    def nombre = "Gustavo"
                    println nombre
                }
            }
            
        }
        stage("Apellido")
        {
            steps
            {
                script
                {
                    def apellido = "Vargas"
                    println apellido
                }
            }
        }
        
        stage("Nombre y apellido")
        {
            steps
            {
                script
                {
                    println nombre + " " + apellido
                }
            }
        }
    }
}
