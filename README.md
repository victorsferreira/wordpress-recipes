# wordpress-recipes

// Adicionar caixa de formulário

function(){
    add_meta_box( 'id', 'título', 'callback that echoes', 'screen', 'normal', 'high' );
}

add_action( 'add_meta_boxes', array( $this, 'add_meta_boxes' ), 30 );
