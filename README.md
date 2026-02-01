# White Ship Project (Work in progress)
Aplicativo mobile em Flutter para acompanhamento de lançamentos da SpaceX. O projeto foca em organização rigorosa utilizando Clean Architecture.

# Tecnologias usadas
- **Linguagem:** Dart
- **Framework:** Flutter
- **API:** SpaceX API v4
- **Arquitetura:** Clean Architecture (Domain, Data, Presentation)
- **Gerenciador de estado:** a definir...

# Estrutura de pastas
O projeto segue a divisão por camadas para garantir desacoplamento:
- **domain:** Entidades puras e interfaces de contratos.
- **data:** Modelos JSON, data sources e implementações de repositórios.
- **presentation:** UI (Widgets) e lógica de estado.

# Requisitos de implementação
- [ ] Consumo do endpoint  `/launches`
- [ ] Tratamento de erros e estados de carregamento
- [ ] Filtro de busca local
- [ ] Separação clara entre `Models`(Data) e `Entities`(Domain)

# Como executar
```
flutter pub get
flutter run
```