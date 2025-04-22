## Spark UI – przegląd najważniejszych sekcji:
- **Jobs** – lista i status wszystkich wykonywanych zadań (jobów). Możemy przejść do konkretnego zadania i zobaczyć szczegółowe informacje dotyczące jego wykonania.

- **Stages** – lista i status poszczególnych etapów (stage’y), które są oddzielone operacjami typu shuffle. Podobnie jak w przypadku jobów, dostępne są szczegóły dotyczące czasu wykonania poszczególnych zadań, ilości danych odczytanych/zapisanych w procesie shuffle itd.

- **Storage** – informacje o danych przechowywanych w pamięci podręcznej (cache). W naszej sytuacji jednak jeszcze tego nie wykorzystaliśmy :)

- **Environment** – podsumowanie konfiguracji klastra, czyli np. czy nasze executory mają przypisaną odpowiednią ilość pamięci lub zasobów CPU.

- **Executors** – lista, status oraz szczegóły dotyczące executorów. W naszym przypadku korzystamy tylko z jednego węzła, więc mamy jedynie pojedynczy executor, który pełni także rolę drivera.

- **SQL/Dataframe** – szczegółowy widok planów wykonania zapytań. Zazwyczaj bardziej czytelny i intuicyjny niż podstawowe widoki.
