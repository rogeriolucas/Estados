# Estados
<?php
<!-- <!-- $Estado= array("ES", "MG", "RJ", "SP") ;

class estado {
	
    public string $sigla;

    public string $nome;

   public function __construct(string $sigla, string $EspiritoSanto ) {
        $this->Es= $Espirito Santo;
        $this->Minas Gerais = $Minas Gerais;
        $this->Sao Paulo = $SP;
      
    }
}
public function estados
$estados = [
    'SP' => 'São Paulo',
    'MG' => 'Minas Gerais',
    'RJ' => 'Rio de Janeiro',
    'ES' => 'Espírito Santo'
];

foreach ($estados as $sigla => $nome) {
    echo $nome . " - " . $sigla . PHP_EOL;
}
}


}




php Tendo os arrays ['ES', 'MG', 'RJ', 'SP'] e ['São Paulo', 'Rio de Janeiro', 'Minas Gerais', 'Espírito Santo'], percorra os vetores dados e crie um outro com a seguinte estrutura: ['ES'=>'Espírito Santo', 'MG'=>'Minas Gerais', 'RJ'=>'Rio de Janeiro', 'SP'=>'São Paulo']. Depois de criado terceiro vetor, leia-o e imprima em cada linha a chave de cada posição e seu respectivo valor separados por "-".












<?php
foreach ($colors as &$color) {
    $color = strtoupper($color);
}
unset($color); /* ensure that following writes to
$color will not modify the last array element */

print_r($colors);
?>
O exemplo acima irá imprimir:

Variedade
(
    [0] => VERMELHO
    [1] => AZUL
    [2] => VERDE
    [3] => AMARELO
)
Este exemplo cria um array na base 1.

Exemplo #14 Array baseado em 1

<?php
$primeiroquarto  = array(1 => 'Janeiro', 'Fevereiro', 'Março');
print_r($primeiroquarto);
?>
O exemplo acima irá imprimir:

Variedade
(
    [1] => 'Janeiro'
    [2] => 'Fevereiro'
    [3] => 'Março'
)
























