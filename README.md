# EPTA_SPACE_PROGRAM
Aplicativo para celular Android de jogo Arcade desenvolvido na plataforma **Unity** (**2020.1.3f1**). Com fins de angariar fundos para a equipe **EPTA** (Equipe de Propulsão e Tecnologia Aeroespacial)

## Plano de gestão para 2021
No primeiro semestre deste ano será desenvolvida a etapa de pré-lançamento do jogo. Tal atividade engloba a partir da versão **0.5.0** até a **1.0.0** e denota todos os desenvolvimentos para terminar o pre-alpha, alpha e todos os betas, sendo a versão **1.0.0** a primeira que será disponibilizada ao público na **Google Play** em meados de **Fevereiro**.

Abaixo encontra-se um roteiro de atividades com datas previstas:

Abaixo encontra-se o roteiro de pessoas responsáveis por cada tópico e a forma como será levado o versionamento em **GIT**:

<div style='text-align:center'>

```plantuml

@startuml

!define DARKBLUE
!includeurl https://raw.githubusercontent.com/Drakemor/RedDress-PlantUML/master/style.puml
skinparam {

ParticipantFontname Times
ParticipantBorderColor white
ParticipantBackgroundColor #282A36
ParticipantFontSize 12

classFontColor white
classFontName Times
classFontSize 16

ArrowFontName Times
ArrowFontSize 14
ArrowColor white

ActorBackgroundColor #282A36
ActorBorderColor white
ActorFontColor white
ActorFontSize 16
ActorFontName Times

SwimlaneTitleFontColor White
SwimlaneBorderColor white
SwimlaneTitleFontSize 16
SwimlaneTitleFontName Times
SwimlaneBorderThickness 2

ActivityBarColor #black

''backgroundColor null 
backgroundColor #282A36
}

|EPTA_SPACE_PROGRAM|
start
|Felipe Ribeiro|
:bug-fixes;
|EPTA_SPACE_PROGRAM|
:0.5.0 - Prealpha inicial - 19/jan;
|EPTA_SPACE_PROGRAM|
fork
|Felipe Ribeiro|
:fix_input_jogador;
fork again
|Matheus Fernandes|
:salvamento_modular;
fork again
|Olavo Inácio|
:trocar_sprites_on_demand;
fork again
|Pedro Melo|
:Queda_da_tela_inicial;
|EPTA_SPACE_PROGRAM|
end fork
stop

@enduml

```
</div>

---
Abaixo encontram-se a ordem de implementação de features:

- Felipe J. O. Ribeiro : bug-fixes : 19/01/2021

- Felipe J. O. Ribeiro : fix_input_jogador: 23/01/2021
