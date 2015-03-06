$(document).ready(function() {

  var favDogs = new Array("3: German Shepard", "6: Golden Retriever", "2: Maltese", "5: Lab", "8: Shih Tzu", "4: Shiba Inu", "9: French Bull Dog", "7: Poodle", "1: Boxer", "0: Yorkie");

  function insertionSort () { 
    for(var i = 1; i < favDogs.length; i++){
    var value = favDogs[i];
    var done = false;
    var j = i - 1;
    while(!done){
        if(favDogs[j] > value){
                favDogs[j + 1] = favDogs[j];
                j = j - 1;
                if(j < 0){
                    done = true;
                }
        }else{
            done = true;
        }
    }
    favDogs[j + 1] = value;
    }
  }

  $('#rankingBox').hide();

  $('#favButton').on('click', function() {
    $('#rankingBox').show();
    $('#rank0').html(favDogs[0]);
    $('#rank1').html(favDogs[1]);
    $('#rank2').html(favDogs[2]);
    $('#rank3').html(favDogs[3]);
    $('#rank4').html(favDogs[4]);
    $('#rank5').html(favDogs[5]);
    $('#rank6').html(favDogs[6]);
    $('#rank7').html(favDogs[7]);
    $('#rank8').html(favDogs[8]);
    $('#rank9').html(favDogs[9]);
    console.log(favDogs);
  })

  $('#sortButton').on('click', function() {
    insertionSort();
    $('#rank0').html(favDogs[0]);
    $('#rank1').html(favDogs[1]);
    $('#rank2').html(favDogs[2]);
    $('#rank3').html(favDogs[3]);
    $('#rank4').html(favDogs[4]);
    $('#rank5').html(favDogs[5]);
    $('#rank6').html(favDogs[6]);
    $('#rank7').html(favDogs[7]);
    $('#rank8').html(favDogs[8]);
    $('#rank9').html(favDogs[9]);
    console.log(favDogs);    
  })
});