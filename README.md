text
# 📱 Projeto Android - Ciclo de Vida das Aplicações

Este projeto tem como objetivo explorar e demonstrar o ciclo de vida das aplicações Android, utilizando uma Activity para exemplificar os diferentes estados e callbacks disponíveis no framework.

---

## 📖 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Ciclo de Vida do Android](#ciclo-de-vida-do-android)


---

## Sobre o Projeto

Este projeto foi desenvolvido para ajudar desenvolvedores a entenderem o ciclo de vida das Activities no Android. Ele implementa os principais métodos de callback (`onCreate`, `onStart`, `onResume`, `onPause`, `onStop`, `onRestart` e `onDestroy`) e exibe logs no Logcat para que os estados possam ser visualizados em tempo real.

---

## Ciclo de Vida do Android

O ciclo de vida de uma Activity no Android é composto por sete principais métodos de callback:

1. **onCreate()**: Chamado quando a Activity é criada pela primeira vez. Usado para inicializar componentes e configurar layouts.
2. **onStart()**: Indica que a Activity está prestes a ser visível ao usuário.
3. **onResume()**: A Activity está em primeiro plano e interativa.
4. **onPause()**: Chamado quando a Activity perde o foco, mas ainda está parcialmente visível.
5. **onStop()**: A Activity não está mais visível.
6. **onRestart()**: Chamado antes de a Activity ser reiniciada após ter sido parada.
7. **onDestroy()**: Chamado antes da destruição da Activity.

Esses métodos permitem gerenciar recursos, salvar estados e otimizar o desempenho da aplicação conforme o usuário navega entre telas ou alterna entre aplicativos.

---


