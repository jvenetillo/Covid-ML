# Covid-ML
#### Sobre a base de dados    
    
Essa base de dados foi fornecido pelo Governo Mexicano (https://datos.gob.mx/busca/dataset/informacion-referente-a-casos-covid-19-en-mexico) e contém uma quantidade enorme de pacientes que estão relacionados à COVID e suas pré-condições.
Em dados brutos são 21 características únicas e 1.048.575 pacientes únicos.      

Para dados booleanos, 1 significa \"Yes\" e 2 significa \"No\".
Valores 97 e 99 são dados faltantes.

* USMR: paciente se tratou em unidade médidas de primeiro, segundo ou terceiro nível.
* MEDICAL_UNIT: tipo de instituição do Sistema Nacional de Saúde que prestou o atendimento.
* SEX: feminino[1] e masculino[2].
* PAIIENT_TYPE: paciente foi hospitalizado ou não.
* DATE_DIED: se paciente morreu, indica a data da morte. 9999-99-99 indica que o paciente está vivo.
* INTUBED: paciente ou conectado ao ventilador ou não.
* PNEUMONIA: paciente com inflamação das vias áereas ou não.
* AGE: idade do paciente.
* PREGNANCY: paciente grávida ou não.
* DIABETES: paciente tem diabete ou não.
* COPD: indica se o paciente tem doença pulmonar obstrutiva crônica(DPOC) ou não.
* ASTHMA: paciente tem asma ou não.
* INMSUPR: paciente é imunossuprimido ou não.
* HYPERTENSION: paciente tem hipertensão ou não.
* OTHER_DISEASE: paciente tem outra doença ou não.
* CARDIOVASCULAR: paciente tem doença relacionada ao coração ou aos vasos sanguíneos.
* OBESITY: paciente é obeso ou não.
* RENAL_CHRONIC: paciente tem doença renal crônica ou não.
* TOBACCO: paciente é tabagista ou não.
* CLASIFFICATION: resultados dos testes de COVID. Valores de 1-3 significam que o paciente foi diagnosticado com covid em graus diferentes. 4 ou acima significa que o paciente não foi diagnosticado com COVID ou o teste foi inconclusivo.
* ICU: paciente foi internado em uma Unidade de Terapia Intensiva(UTI) ou não.
