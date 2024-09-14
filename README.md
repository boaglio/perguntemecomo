# Spring Boot espertinho

## pergunte me como 

### Pré-requisitos

* [instalar o GCloud](https://cloud.google.com/sdk/docs/install) na sua máquina
* ter uma conta ativa na Google Cloud
* ter uma aplicação ativa na [Google Cloud](https://console.cloud.google.com/cloud-resource-manager) 
* ativar o uso da [Vertex AI API](https://console.developers.google.com/apis/api/aiplatform.googleapis.com/overview)

### Exemplo de uso

```
$ http :8080/ai/generate?message="Quem é Tom Bombadil?"
{
    "generation": "Tom Bombadil é uma figura enigmática e poderosa no universo de Tolkien, aparecendo no livro \"O Senhor dos Anéis\". Ele é descrito como um homem velho e alegre, com um chapéu verde e botas amarelas, que vive na Floresta Velha, uma região antiga e mágica na Terra-média.\n\nApesar de seu papel relativamente pequeno na história, Tom Bombadil possui várias características que o tornam uma figura intrigante:\n\n* **Poder sobrenatural:** Tom é capaz de controlar a natureza e as criaturas mágicas da Floresta Velha, incluindo o próprio Barão de Carrock, um espírito maligno que a assombra. Ele também parece ser imune aos poderes do Um Anel, o que sugere uma força ainda maior.\n* **Mistério:** Tolkien nunca revelou a verdadeira natureza de Tom Bombadil. Ele é descrito como um \"antigo\", sugerindo que ele está presente na Terra-média desde tempos imemoriais, mas sua origem e propósito permanecem obscuros.\n* **Independência:** Tom não parece se alinhar com nenhuma das forças do bem ou do mal na Terra-média. Ele é independente e parece ter seus próprios propósitos, que não são revelados ao leitor.\n\n**Alguns teóricos acreditam que Tom Bombadil pode ser:**\n\n* **Uma encarnação de Eru Ilúvatar, o Criador:**  Sua imuneidade ao Um Anel e seu poder sobre a natureza sugerem uma força divina.\n* **Um espírito primordial da Terra-média:**  Sua presença antiga e seu domínio sobre a natureza o colocam como um guardião da própria terra.\n* **Uma entidade independente, não explicada por Tolkien:**  Talvez Tom seja simplesmente uma figura única e inexplicável, um mistério que Tolkien escolheu deixar sem solução.\n\nIndependentemente de sua verdadeira natureza, Tom Bombadil é uma figura memorável e fascinante no universo de Tolkien. Ele representa a magia, a independência e o mistério da Terra-média, e sua presença adiciona uma camada de complexidade e profundidade à história.\n"
}
```