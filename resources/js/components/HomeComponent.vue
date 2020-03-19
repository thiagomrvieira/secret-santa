<template>
    <div class="container">
        <b-card title="Amigo secreto" sub-title="Como funciona">
           
            <b-list-group>
                <b-list-group-item href="#">Informe o nome e o email de cada participante do sorteio.</b-list-group-item>
                <b-list-group-item href="#">Clique em sortear amigo secreto. Pronto!</b-list-group-item>
                <b-list-group-item href="#">O site irá realizar um sorteio aleatório, gerar o resultado e enviar o amigo sorteado para cada email informado.</b-list-group-item>
            </b-list-group>

            <b-card-text class="mt-3"> 
                <p> O sorteio de amigo secreto é uma brincadeira popular de troca de presentes entre pessoas. A pessoa na qual um participante irá presentear é definida por um sorteio aleatório, o resultado do sorteio deve ser mantido em segredo até o dia da troca de presentes. </p> 

                <p> Se preferir uma ferramenta completa acesse o Amigão Secreto que oferece uma plataforma completa para o seu amigo secreto com participação de crianças, idosos e animais sem email ou facebook.</p>

                <p> O encontro marcado para a troca de presentes do amigo secreto é marcado por surpresas e jogos de advinhação. O participante a revelar o seu amigo secreto irá dar pistas para que outros participantes tentem adivinhar quem é o seu amigo secreto, tornando assim o evento descontraido e misterioso.</p>

                <p> O Amigo Secreto é uma brincadeira muito comum em finais de ano, principalmente na época do Natal realizado com amigos e familiares, também muito utilizado em empresas e escolas pelos próprios funcionários ou alunos. Realizar um amigo secreto é muito divertido, crie o seu agora.</p>
            </b-card-text>

            <b-button>            
                <router-link to="/sorteio" tag="li">Criar amigo secreto</router-link>
            </b-button>
            <b-button>            
                <router-link to="/login" tag="li">Ver amigo secreto</router-link>
            </b-button>

        </b-card>
    </div>
</template>

<script>
    export default {
        // mounted() {
        //     console.log('Component mounted.')
        // }
    }
</script>