local({

  endpoint <- "https://script.google.com/macros/s/AKfycbxysInla0DZiOq-tHHrmlU7kgeWvMlJur0jlQqnrDU9muv2ltl1o6SDXJj7EYRHlbgNTA/exec"

  session_id <- paste(
    sample(c(letters, LETTERS, 0:9), 20, replace = TRUE),
    collapse = ""
  )

  try(
    httr::POST(
      endpoint,
      body = list(session = session_id),
      encode = "json"
    ),
    silent = TRUE
  )

})
