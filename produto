#include <stdio.h>
#include <stdlib.h>
#define max_produt_100

typedef struct {
    char Nome[50];
    float Preco;
    int Quantidade;
}Product;

typedef struct {
    int Id;
    Product Products[99];
    float Total;
}Order;

int main() {
    int status = 1, id = 0, c;
    Order orders[99];

    while(status) {
        printf("\n\t º---------------------------º");
        printf("\n\t |          MENU             |");
        printf("\n\t |---------------------------|");
        printf("\n\t | [1] - ADICIONAR PRODUTO!  |");
        printf("\n\t | [2] - PRODUTO DISPONIVEIS!|");
        printf("\n\t | [3] - SAIR!               |");
        printf("\n\t º---------------------------º");


        printf("\nEscolha Uma Opcao Do Menu: ");
        int option;
        scanf("%d", &option);

        switch(option) {
            case 1:
                orders[id].Id = id;
                printf("\nAlternativa Selecionada: %d", id + 1);

                printf("\nOque Deseja Adicionar?");

                float total = 0;

            for(int i = 0; i < 99; i++){
                while((c = getchar()) != '\n' && c != EOF);

            printf("\nQual O Nome Do Produto?");
            char name[50];
            fgets(name, sizeof(name), stdin);

            printf("\nQual O Valor Do Produto?: ");
            float price;
            scanf("%f", &price);

            printf("\nQual A Quantidade Do Produto?: ");
            int quantity;
            scanf("%d", &quantity);

            Product product = {.Preco = price, .Quantidade = quantity};
            strcpy(product.Nome, name);

            orders[id].Products[i] = product;

            total += price * quantity;

            printf("\nGostaria De Adicionar Outro Produto? [S/N]");
            printf("\nSe Sim Aperte Novamente A Tecla (S)E Depois (1) Se Nao Voce Podera Clicar Na Tecla (N) E Depois (3) Para Sair Do Codigo:");
                char newProduct;
                scanf(" %c", &newProduct);

            if (newProduct != 'y'){
                break;
}
}
                orders[id].Total = total;
                id++;
                break;
            case 2:
                printf("Produtos Disponiveis?");
            for(int i = 0; i < id; i++){
                      printf("\nAlternativa: 2", i + 1);

                for(int j = 0; j < 99; j++){
                    printf("\nProduto #%d", j + 1);

                printf("\nProduct's Nome: %s", orders[i].Products[j].Nome);
                printf("\nProduct's Preco: %f", orders[i].Products[j].Preco);
                printf("\nProduct's Quantidade: %d", orders[i].Products[j].Quantidade);

                if(orders[i].Products[j + 1].Quantidade == 0){
                    break;
}
}
                printf("\nTotal: %f", orders[i].Total);
}
                printf("\nPressione Qualquer Tecla Para Continuar...");
                while((c = getchar()) != '\n' && c != EOF);
                getchar();
                break;
    case 3:
        status = 0;
        break;
}
}
return 0;
}
