stage("inputs -- drop down box"){
 userInput = input(id: 'userInput',    
                  message: 'Choose an environment',    
                  parameters: [
                    [$class: 'ChoiceParameterDefinition', choices: "Dev\nQA\nProd", name: 'Env']
                  ]  
  ) 
}
