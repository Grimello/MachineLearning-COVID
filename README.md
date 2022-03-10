# MachineLearning-COVID
Projeto de Machine Learning para previsão de casos de COVID a partir do diagnóstico de sintomas e informações do paciente.

A descrição das variáveis contidas no dataset pode ser encontradas a seguir:

id: Identificação do paciente
sex: Sexo do Paciente (0 - Homem / 1 - Mulher)
patient_type: Se o paciente foi dispensado para casa (1) ou se foi internado (0)
intubed: Seo paciente foi intubado ou não
pneumonia: Se o paciente apresentou pneumonia ou não
age: Idade do Paciente
pregnancy: Se a paciente estava grávida ou não (para pacientes mulheres)
diabetes: Se o paciente tem diabetes ou não
copd: Se opaciente tem COPD ou não
asthma: Se o paciente tem Asma ou não
inmsupr: Se o paciente apresentou Imunosupressão ou não
hypertension: Se o paciente tem hipertensão ou não
ohter_disease: Se o paciente tem outras doenças ou não
cardiovascular: Se o paciente tem doenças cardiácas ou não
obesity: Se o paciente tem obesidade ou não
renal_chronic: Se o paciente tem problemas renais ou não
tobacco: Se o paciente é fumante ou não
contact_other_covid: Se o paciente teve contato com outras pessoas diagnosticadas com covid
icu: Se o paciente precisou ser internado na UTI
covid_res: Se o resultado do teste foi Positivo ou Negativo


O projeto foi separado em algumas seções, conforme descritas a seguir:

-Preparação dos Dados e Verificação de Consistência: Neste tópico foi realizada a verificação da consistência dos dados e efetuar eventuais modificações na base de dados. Alguns dos procedimentos realizados: Remoção e/ou tratamento de valores faltantes, remoção de duplicatas, ajustes dos tipos de variáveis, análise de outliers entre outras;

-Análise Exploratória dos Dados: Nesta parte do projeto foram desenvolvidas análises e gráficos a respeito dos dados qutilizados. Foram retirados o máximo de informações e suas correlações.

-Modelagem dos Dados: Nesta parte modelamos os resultados dos exames de COVID (covid_res). Foram treinados três modelos e, de acordo com a métrica de avaliação escolhida, foi definido o melhor modelo a ser utilizado.

-Otimização do Modelo: A partir do modelo escolhido aprimoramos e garantimos um melhor desempenho no modelo através de validação cruzada, otimização de parâmetros com GridSearchCV ou RandomizedSearchCV e ateste de diferentes thresholds.

-Conclusões: Descrição das conclusões sobre o desenvolvimento do modelo e os resultados obtidos.
