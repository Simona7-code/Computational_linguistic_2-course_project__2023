La cartella è così composta:

- data :
	- Dataset :

		- dataset_ironita_2018.csv -->  contiene il dataset ufficiale;
		- ironita2018-guidelines170918.pdf --> contiene il paper di presentazione della task;

	- profiling_output :

		- profiling_test :

			- test --> contiene i file restituiti da profilingUD, ovvero un file contente l'annotazione per ogni tweet del test set;
			- 6711.csv --> contiene le feature linguistiche estratte per ogni tweet del test set;
			- profiling-legend.txt --> contiene la legenda delle feature linguistiche estratte dal sistema profilingUD;

		- profiling_training :

			- training --> contiene i file restituiti da profilingUD, ovvero un file contente l'annotazione per ogni tweet del training set;
			- 6712.csv -->  contiene le feature linguistiche estratte per ogni tweet del training set;
			- profiling-legend.txt --> contiene la legenda delle feature linguistiche estratte dal sistema profilingUD;

	- word_embeddings : contiene il file contenente i word embeddings specifici per tweet in lingua italiana; 

- consegna_progetto.pdf --> contiene le richieste di progetto;

- IronITA.ipynb --> contiene l'implementazione delle prime tre richieste di progetto;

- IronITA_BERT.ipynb --> contiene l'implementazione di un classificatore basato su un neural language model, ovvero l'ultima richiesta di progetto; il file letto per realizzarlo è dataset_ironita_2018.csv (contenuto in Dataset); tenere in considerazione di cambiare il path di lettura nel caso di esecuzione locale, in quanto quello presente nel file è stato eseguito su Google Colab ed è stato letto direttamente dal path su Google Drive;

- Relazione_544298.pdf --> relazione sul progetto;