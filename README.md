
```{r, echo=FALSE, eval=TRUE, results="asis"}
travis_url <- "https://travis-ci.org/LuisMDeveloper/FinancialAssistant.svg?branch="
shield <- paste0("[![Build Status](",
                 travis_url,
                 system("git rev-parse --abbrev-ref HEAD", intern = TRUE),
                 ")](https://travis-ci.org/LuisMDeveloper/FinancialAssistant)
cat(shield)
```

# FinancialAssistant
