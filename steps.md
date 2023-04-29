user click
    []invoke mimicServerCall => .then?
    [] no errors
        [] change empty_heart to full_heart
        [] .add activated-heart to class => change innerText?
    [] when err occurs => .catch? 
        []display error message(modal-message)
        []invoke setTimeout to 3000 => .add hidden to id modal
    []change the heart back to empty-heart
        [].remove activated-heart => change innerText?