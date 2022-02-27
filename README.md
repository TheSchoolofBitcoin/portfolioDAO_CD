This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

# diplomaDAO Conceptual Design (CD)
#### The School of Bitcoin | Stacks AUS/NZ

TSOBTC is committed to a transparent process for creating diplomaDAO.
- Project Tracker: Curriculum DAO Concept Design (https://github.com/orgs/TheSchoolofBitcoin/projects/1)
- b0mission: https://github.com/TheSchoolofBitcoin/curriculumDAO_CD/issues/1
- b1community: https://github.com/TheSchoolofBitcoin/curriculumDAO_CD/issues/4
- b2media: https://github.com/TheSchoolofBitcoin/curriculumDAO_CD/issues/5
- b3now: https://github.com/TheSchoolofBitcoin/curriculumDAO_CD/issues/6
- b4portfolio: https://github.com/TheSchoolofBitcoin/curriculumDAO_CD/issues/7
- b5essay: https://github.com/TheSchoolofBitcoin/curriculumDAO_CD/issues/8
- b6story: https://github.com/TheSchoolofBitcoin/curriculumDAO_CD/issues/9
- b7learn: https://github.com/TheSchoolofBitcoin/curriculumDAO_CD/issues/10
- b8play: https://github.com/TheSchoolofBitcoin/curriculumDAO_CD/issues/11
- b9journal: https://github.com/TheSchoolofBitcoin/curriculumDAO_CD/issues/12

### End Result
After working through each of these issues, we will have a Stacks NFT Minting dApp that allows people to mint the NFT associated with this course designed by a member from the bitcoin.design community. The metadata below represents the NFT's proof-of-work.

```
bitEntryProgram: {
  ourStoryRecordStore:               "432API",
  bioMemeticOrganization:            "The School of Bitcoin",
  longPlay:                          "Stacks Australia/New Zealand",
  b0mission: {
    groove:                          "gr0ourSource",
    projectFocus:                    "goals",
    gr0v0ego: {
      institutionQuestion:           "What global institution will you explore?"
      institution:                   "[INSTITUTION]",

      challengeQuestion:             "What challenge does this institution create?"
      challenge:                     "[CHALLENGE]",

      egoQuestion:                   "What human trait contributes to this challenge?"
      ego:                           "[EGO]",

      bookEgoQuestion:               “What book will represent how this book explores this challenge?”,
      bookEgoTitle:                  "[BOOK_EGO_TITLE]",
      bookEgoAuthor:                 "[BOOK_EGO_AUTHOR]",

      gr0v0Statement:                "Our __[INSTITUTION]__ institution is letting __[EGO]__ contribute to __[CHALLENGE]__. This Curriculum DAO uses __[BOOK_EGO_TITLE]__ by __[BOOK_EGO_AUTHOR]__ to understand our community's challenges."
    },
    gr0v1biomimicry: {
      natureMentorQuestion:          "What system in nature can use the challenge to create a benefit?",
      natureMentor:                  "[NATURE_MENTOR]",
      
      mentorBenefitQuestion:         "What benefit does the system in nature create from the challenge?,
      mentorBenefit:                 "[MENTOR_BENEFIT]",
      
      bookBioQuestion:               "What book will help explore the system in nature?",
      bookBioTitle:                  "[BOOK_BIO_TITLE]",
      bookBioAuthor:                 "[BOOK_BIO_AUTHOR]",
      
      gr0v1Statement:                "__[NATURE_MENTOR]__ use __[CHALLENGE]__ to create __[MENTOR_BENEFIT]__. We learn from __[BOOK_BIO_TITLE]__ by __[BOOK_BIO_AUTHOR]__ to think of creative solutions to our challenges."
    },
    gr0v2willpower: {
      bookWillQuestion:              “What book will define how your community operates?",
      bookWillTitle:                 "[BOOK_WILL_TITLE]",
      bookWillAuthor:                "[BOOK_WILL_AUTHOR]",
      
      gr0v2Statement:                "We are developing a Curridulum DAO that learns from __[NATURE_MENTOR]__ so we can create __[MENTOR_BENEFIT]__ through __[CHALLENGE]__. We learn from __[BOOK_WILL_TITLE]__ by __[BOOK_WILL_AUTHOR]__ to help define how we operate."
    },
    gr0v3song: {
      songTitle:                     "[SONG_TITLE]",
      songArtist:                    "[SONG_ARTIST]",
      
      gr0v3Statement:                "__[SONG_TITLE]__ by __[SONG_ARTIST]__ represents our project's goals."
    }
  },
  
  b1community: {
    groove:                          “gr1ourJourney”,
    projectFocus:                    "Community Roadmap",
    gr1v0decentralization: {
      industry:                      "Education",
      service:                       "base curriculum for crypto",
      focus:                         "Bit Entry Program",
      serviceInspiration:            "[SERVICE_INSPIRATION]",
      serviceInspiractionURL:        "[SERVICE_INSPIRATION_URL]"
    },
    gr1v1space: {
      communityProject:              "[COMMUNITY_PROJECT]",
      communityProjectExampleURL:    "[COMMUNITY_PROJECT_EXAMPLE_URL]",
      promotedProject:               "[PROMOTED_PROJECT]",
      promotedProjectURL:            "[PROMOTED_PROJECT_URL]"
    },
    gr1v2time: {
      b0mission: {
        deliverableFormat:           “Open Source Mission: Concept Design”,
        deliverableDate:             “YYYY MM DD”
        deliverableURL:              “[DELIVERABLE_URL]",
        deliverablePOWURL:           “[DELIVERABLE_POW_URL]”
      },
      b1community: {
        deliverableFormat:           “Open Source Community: Concept Design”,
        deliverableDate:             “YYYY MM DD”
        deliverableURL:              “[DELIVERABLE_URL]",
        deliverablePOWURL:           “[DELIVERABLE_POW_URL]”
      },
      b2media: {
        deliverableFormat:           “Brand Identity: Concept Design”,
        deliverableDate:             “YYYY MM DD”
        deliverableURL:              “[DELIVERABLE_URL]",
        deliverablePOWURL:           “[DELIVERABLE_POW_URL]”
      },
      b3now: {
        deliverableFormat:           “Marketing Strategy: Concept Design”,
        deliverableDate:             “YYYY MM DD”
        deliverableURL:              “[DELIVERABLE_URL]",
        deliverablePOWURL:           “[DELIVERABLE_POW_URL]”
      },
      b4portfolio: {
        deliverableFormat:           “Marketplace: Concept Design”,
        deliverableDate:             “YYYY MM DD”
        deliverableURL:              “[DELIVERABLE_URL]",
        deliverablePOWURL:           “[DELIVERABLE_POW_URL]”
      },
      b5essay: {
        deliverableFormat:           “Litepaper: Concept Design”,
        deliverableDate:             “YYYY MM DD”
        deliverableURL:              “[DELIVERABLE_URL]",
        deliverablePOWURL:           “[DELIVERABLE_POW_URL]”
      },
      b6story: {
        deliverableFormat:           “Storyboard: Concept Design”,
        deliverableDate:             “YYYY MM DD”
        deliverableURL:              “[DELIVERABLE_URL]",
        deliverablePOWURL:           “[DELIVERABLE_POW_URL]”
      },
      b7learn: {
        deliverableFormat:           “Curriculum: Concept Design”,
        deliverableDate:             “YYYY MM DD”
        deliverableURL:              “[DELIVERABLE_URL]",
        deliverablePOWURL:           “[DELIVERABLE_POW_URL]”
      },
      b8play: {
        deliverableFormat:           “Community Game: Concept Design”,
        deliverableDate:             “YYYY MM DD”
        deliverableURL:              “[DELIVERABLE_URL]",
        deliverablePOWURL:           “[DELIVERABLE_POW_URL]”
      },
      b9journal: {
        deliverableFormat:           “Note Taking Strategy: Concept Design”,
        deliverableDate:             “YYYY MM DD”
        deliverableURL:              “[DELIVERABLE_URL]",
        deliverablePOWURL:           “[DELIVERABLE_POW_URL]”
      },
    gr1v3song: {
      songTitle:                     "[SONG_TITLE]",
      songArtist:                    "[SONG_ARTIST]",
      
      gr1v3Statement:                "__[SONG_TITLE]__ by __[SONG_ARTIST]__ represents our project's community roadmap."
    }
  },
  b2media: {
    gr2v0relate: {
    
    },
    gr2v1body: {
    
    },
    gr2v2mind: {
    
    },
    gr2v3song: {
      songTitle:                     "[SONG_TITLE]",
      songArtist:                    "[SONG_ARTIST]",
      
      gr2v3Statement:                "__[SONG_TITLE]__ by __[SONG_ARTIST]__ represents our project's brand identity."
    }
  },
  b3now: {
    gr3v0shadow: {
      
    },
    gr3v1presence: {
     
    },
    gr3v2music: {
      
    },
    gr3v3song: {
      songTitle:                     "[SONG_TITLE]",
      songArtist:                    "[SONG_ARTIST]",
      
      gr2v3Statement:                "__[SONG_TITLE]__ by __[SONG_ARTIST]__ represents our project's marketing strategy."
    }
  },
  b4portfolio: {
    gr4v0create: {
      /// This section defines the structure of the case studies the Curriculum DAO will create to update the community ///
    },
    gr4v1habit: {
      /// This section defines the content schedule (strategy is b3now) across social media. Also schedule for case study updates. ///
    },
    gr4v2wealth: {
      /// This section defines the wealth generation targets as a result of the conceptual tokenomics design. ///
      wealthGenerationTarget:        “ ”,
      communityInvestmentTarget:     “ ”,
      freelancerPayoutTarget:        “ ”
    },
    gr4v3song: {
      songTitle:                     "[SONG_TITLE]",
      songArtist:                    "[SONG_ARTIST]",
      
      gr4v3Statement:                "__[SONG_TITLE]__ by __[SONG_ARTIST]__ represents our project's value proposition."
    }
  },
  b5essay: {
    gr5v0belief: {
      /// Section of the litepaper that defines the basis for the projects belief that this Curriculum DAO will help with the defined challenge ///
    },
    gr5v1science: {
      /// Section of the litepaper that outlines the scientific process used to design the Curriculum DAO case study experiments ///
    },
    gr5v2sensemaking: {
      /// Section of the litepaper that outlines current biases and counter arguments with evidence to create a more balanced perspective for the challenge. ///
    },
    gr5v3song: {
      songTitle:                     "[SONG_TITLE]",
      songArtist:                    "[SONG_ARTIST]",
      
      gr5v3Statement:                "__[SONG_TITLE]__ by __[SONG_ARTIST]__ represents our project's litepaper."
    }
  },
  b6story: {
    gr6v0mythology: {
      /// Define how the litepaper will be transformed into an imaginative myth (comic/graphic novel/short stories/etc.) and the narratives story arch ///
    },
    gr6v1spirituality: {
      /// Moral of the creative story for the protagonist (Curriculum DAO). These are related to the results of the experiments from gr5v1science ///
    },
    gr6v2consciousness: {
      /// Moral of the creative story for the institution defined in b0mission  ///
    },
    gr6v3song: {
      songTitle:                     "[SONG_TITLE]",
      songArtist:                    "[SONG_ARTIST]",
      
      gr6v3Statement:                "__[SONG_TITLE]__ by __[SONG_ARTIST]__ represents our project's mythology."
    }
  },
  b7learn: {
    gr7v0ecology: {
      /// Didactic financial literacy course through an ecological lens  ///
    },
    gr7v1physiology: {
      /// Didactic financial literacy course through an physiological lens  ///
    },
    gr7v2sociology: {
      /// Didactic financial literacy course through an sociological lens  ///
    },
    gr7v3song: {
      songTitle:                     "[SONG_TITLE]",
      songArtist:                    "[SONG_ARTIST]",
      
      gr7v3Statement:                "__[SONG_TITLE]__ by __[SONG_ARTIST]__ represents our project's curriculum."
    }
  },
  b8play: {
    gr8v0values: {
      /// Define rules of the community game  ///
    },
    gr8v1vision: {
      /// Define the intended outcomes of the game  ///
    },
    gr8v3game: {
      /// Design, develop, and deploy the game  ///
    },
    gr8v3song: {
      songTitle:                     "[SONG_TITLE]",
      songArtist:                    "[SONG_ARTIST]",
      
      gr8v3Statement:                "__[SONG_TITLE]__ by __[SONG_ARTIST]__ represents our project's community game."
    }
  },
  b9journal: {
    /// This repository represents journal to serve as the proof-of-work for this Curriculum DAOs NFT  ///
  },
}
```

