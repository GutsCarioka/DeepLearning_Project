# DeepLearning_Project
Projeto de Deeplearning em python 
Software desenvolvido em 2024 como projeto final para a disciplina de Inteligencia Artificial na minha faculdade de Analise e desenvolvimento de sistemas

# Tecnologia Utilizadas: 
  <img aling="center" alt=html5 src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />


# Descrição do Projeto
monitoramento de diabetes em Python, utilizando redes neurais com Keras. 
O objetivo é prever a probabilidade de um usuário desenvolver diabetes a partir de dados de entrada. O maior desafio foi integrar o input do usuário ao fluxo de validação da IA, originalmente treinada apenas com arquivos CSV. A solução foi criar uma função capaz de inserir esses dados no processo de verificação da rede. Esse projeto me deu experiência prática com IA, testes, tratamento de erros e principalmente com documentação detalhada, já que precisei explicar todo o processo em sala de aula.




# Gif descritivo do treinamento da rede neural:
  


https://github.com/user-attachments/assets/08c20690-e004-4aa5-a9c1-b9801513a5a7








# Descritivo: 
Inicialmente, carregamos dados médicos de pessoas indianas com diabetes. Em seguida, criamos uma linha de código que separa os dados em entradas e saídas — sendo as entradas as informações do paciente e a saída se o paciente tem ou não diabetes. Depois, compilamos os dados e treinamos o modelo. O treinamento ocorre por meio de épocas, cada uma dividida em lotes. Uma época representa uma passagem por todas as linhas do conjunto de testes, enquanto um lote é composto por uma ou mais amostras (quantidade definida pelo usuário) consideradas pelo modelo antes da atualização dos seus pesos.
Aqui, executamos 150 épocas com lotes de tamanho 10 (um número considerado pequeno). Nesse processo, o modelo verifica o mesmo documento 150 vezes. Por fim, avaliamos a acurácia, ou seja, o modelo informa sua porcentagem de acurácia com base nos dados fornecidos.
Entendo que essa explicação possa parecer um pouco superficial, mas acredito que até a apresentação ela estará mais precisa e assertiva.
