<?php
function wpto_shortmessage_string_callback( $msg_label ){
    $msg_label = __( 'Extra Note', 'wpt_pro' );
    return $msg_label;
}
add_filter( 'wpto_shortmessage_string' , 'wpto_shortmessage_string_callback' );
