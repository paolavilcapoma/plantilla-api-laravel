<?php

namespace app\Models\v1;
use BinaryCabin\LaravelUUID\Traits\HasUUID;
use Illuminate\Database\Eloquent\Model;

class cargo extends Model
{
    use HasUUID;
    protected $table='cargo';
    protected $primarykey="id";
    //poner que el id no es incremental 
    public $incrementing=false;
    //y se debe especificar el tipo de dato
    protected $KeyTipe="string";
    protected $uuidFieldName='id';
    protected $nombre='nombre';
    protected $descripcion='descripcion';
    protected $esactivo='esactivo';
}